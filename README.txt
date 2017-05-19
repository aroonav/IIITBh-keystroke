
1. Title: IIITBh-keystrokes Database

2. Sources:
         (a) Creator: Aroonav Mishra, Goutam Das, Asmi Pattnaik
         (b) Date: May, 2017

3. License

This IIITBh-keystrokes dataset is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/

4. Past Usage:
     1. Mishra A, Das G, Pattnaik A. "Classifying users on the basis of keystroke dynamics". Link: https://github.com/aroonav/aroonav.github.io/blob/master/files/Major.pdf

5. Relevant Information:
     --- An arbitrary password would be typed by all the test subjects. The password chosen was: .xat17padn
     --- The features extracted for each key were:
                * The hold time for a key
                * The KeyDown-KeyUp time between the key and the next key
                * The KeyDown-KeyDown time between the key and the next key(which is effectively a linear combination of the first two features).
                We also chose to consider the Enter key as a part of the password effectively making it a 11 character password.

6. Number of Instances:
IIITBh-Big.csv:   1800 (150 in each of 12 classes/subjects)
IIITBh-Small.csv: 1250 (250 in each of 05 classes/subjects)

7. Number of Attributes: The subject/class, 2 session attributes, 31 numeric, predictive attributes.
     Total: 34 attributes

8. Attribute Information:
    (1) subjects/classes
        IIITBh-Big.csv:     subject0, subject1, subject2, subject3, subject4, subject5, subject6, subject7, subject8, subject9, subject10, subject11.
        IIITBh-Small.csv:   subject2, subject4, subject6, subject12, subject13
    (2) sessionIndex
        IIITBh-Big.csv:     1-6
        IIITBh-Small.csv:   1-10
    (3) rep: 1-25
    (4) H.period:       Hold time for key period.
    (5) DD.period.x:    Time between the down events of key period and key x.
    (6) UD.period.x:    Time between the up and down events of key period and key x respectively.
    (7) H.x:            Hold time for key x.
    (8) DD.x.a:         Time between the down events of key x and key a.
    (9) UD.x.a:         Time between the up and down events of key x and key a respectively.
    (10) H.a:           Hold time for key a.
    (11) DD.a.t:        Time between the down events of key a and key t.
    (12) UD.a.t:        Time between the up and down events of key a and key t respectively.
    (13) H.t:           Hold time for key t.
    (14) DD.t.1:        Time between the down events of key t and key 1.
    (15) UD.t.1:        Time between the up and down events of key t and key 1 respectively.
    (16) H.1:           Hold time for key 1.
    (17) DD.1.7:        Time between the down events of key 1 and key 7.
    (18) UD.1.7:        Time between the up and down events of key 1 and key 7 respectively.
    (19) H.7:           Hold time for key 7.
    (20) DD.7.p:        Time between the down events of key 7 and key p.
    (21) UD.7.p:        Time between the up and down events of key 7 and key p respectively.
    (22) H.p:           Hold time for key p.
    (23) DD.p.a:        Time between the down events of key p and key a.
    (24) UD.p.a:        Time between the up and down events of key p and key a respectively.
    (25) H.a:           Hold time for key a.
    (26) DD.a.d:        Time between the down events of key a and key d.
    (27) UD.a.d:        Time between the up and down events of key a and key d respectively.
    (28) H.d:           Hold time for key d.
    (29) DD.d.n:        Time between the down events of key d and key n.
    (30) UD.d.n:        Time between the up and down events of key d and key n respectively.
    (31) H.n:           Hold time for key n.
    (32) DD.n.Return:   Time between the down events of key n and key Return.
    (33) UD.n.Return:   Time between the up and down events of key d and key Return respectively.
    (34) H.Return:      Hold time for key Return.

9. Missing Attribute Values: None

10. Class Distribution:
    IIITBh-Big.csv:   8.33% for each of 12 classes
    IIITBh-Small.csv: 20% for each of 5 classes.

11. Summary Statistics:
IIITBh-Big.csv
Attributes  Min             Max             Average         Std. Dev.       Class Correlation
H.period    0.0372209549    0.1967558861    0.100556218     0.0170272491    -0.3496536339
DD.period.x 0.040774107     2.6198830605    0.3455800267    0.269303119     0.1430667785
UD.period.x -0.0741939545   2.4231271744    0.2450238087    0.2723396748    0.1633326808
H.x         0.0530309677    0.2938530445    0.1383802915    0.0372044456    0.3375718718
DD.x.a      0.0043771267    0.911454916     0.1229926284    0.0594223098    0.1207986174
UD.x.a      -0.153097868    0.6552350521    -0.015387663    0.0750893396    -0.0716618563
H.a         0.0769650936    0.2963819504    0.1628486031    0.0324120385    0.2727393232
DD.a.t      0.0799059868    1.5423250198    0.2890641728    0.1228425621    0.0585824065
UD.a.t      -0.0538229942   1.4214441776    0.1262155697    0.120493876     -0.013640731
H.t         0.0518770218    0.1871049404    0.098791328     0.0173360299    -0.1334796855
DD.t.1      0.0531630516    4.3694040775    0.3226174096    0.2857783759    0.0366980066
UD.t.1      -0.0084109306   4.1961131096    0.2238260816    0.2831689959    0.045208002
H.1         0.0558559895    0.2301499844    0.1325932998    0.0270389117    0.4076302353
DD.1.7      0.059981823     2.1304748058    0.3192274691    0.1847957031    0.0126033324
UD.1.7      -0.0814311504   2.0020139217    0.1866341693    0.1854043503    -0.0468858268
H.7         0.0056040287    0.1539950371    0.0930150329    0.0139944423    -0.0080400482
DD.7.p      0.232115984     2.4948239327    0.5329688917    0.1987647822    0.1691368232
UD.7.p      0.1419529915    2.4049758911    0.4399538589    0.1954873244    0.1725480663
H.p         0.043307066     0.2416360378    0.101007139     0.0170582477    -0.3112921694
DD.p.a      0.0184600353    1.3215279579    0.1327148782    0.0828204429    0.1853185264
UD.p.a      -0.1476640701   1.2078990936    0.0317077392    0.0821818044    0.2513726914
H.a         0.07634902      0.3681759834    0.1662526679    0.0362662853    0.1973142945
DD.a.d      0.0402748585    1.6312050819    0.211070945     0.1119286792    0.3553135976
UD.a.d      -0.1889350414   1.4741790295    0.0448182771    0.1205286035    0.2705907497
H.d         0.0544400215    0.2266600132    0.131205263     0.0266289272    0.1014094249
DD.d.n      0.0299911499    1.7285330296    0.2689312124    0.1523928582    0.1213879392
UD.d.n      -0.0926718712   1.5733890533    0.1377259494    0.1563662947    0.1010334794
H.n         0.004858017     0.1568470001    0.093796699     0.0134734968    -0.227834253
DD.n.Return 0.1379170418    4.9996948242    0.4688869088    0.3026068719    0.1257543893
UD.n.Return 0.0402531624    4.8762419224    0.3750902098    0.3018526362    0.1362382219
H.Return    0.042372942     0.2652411461    0.1025990627    0.0239625681    -0.5181031489

IIITBh-Small.csv
Attributes  Min             Max             Average         Std. Dev.       Class Correlation
H.period    0.0212709904    0.2131199837    0.1024969666    0.0260370764    -0.0390461674
DD.period.x 0.0501329899    1.4706430435    0.2047272091    0.1173599349    -0.0165917976
UD.period.x -0.0809259415   1.3481080532    0.1022302425    0.1157255588    -0.0080411298
H.x         0.0338029861    0.2569689751    0.1504362827    0.0301380271    0.2154666562
DD.x.a      0.0033900738    0.9961810112    0.1131241333    0.0536512798    -0.0070351105
UD.x.a      -0.1622040272   0.9623780251    -0.0373121494   0.0622528844    -0.1103753292
H.a         0.0563411713    0.3026809692    0.1513254633    0.0237087985    0.1893399462
DD.a.t      0.0404789448    1.2550981045    0.229078821     0.0994702023    -0.0157016824
UD.a.t      -0.0991029739   1.0736169815    0.0777533577    0.0958398388    -0.0631352498
H.t         0.0186030865    0.1727490425    0.0916633537    0.0248862602    -0.2790682087
DD.t.1      0.0913310051    3.9856469631    0.2542554232    0.1806761682    0.061698593
UD.t.1      0.0136380196    3.9045159817    0.1625920694    0.1795659877    0.1007564386
H.1         0.0310029984    0.2264618874    0.12785835      0.0197065048    0.3394252573
DD.1.7      0.063284874     1.6327588558    0.1890149914    0.1160700137    0.1494779524
UD.1.7      -0.081788063    1.4889519215    0.0611566414    0.114459642     0.0931421969
H.7         0.0150630474    0.1629719734    0.0815022474    0.0185494886    -0.2509887532
DD.7.p      0.2404251099    1.4826219082    0.4406190846    0.1295475196    0.1795776744
UD.7.p      0.1607909203    1.3860270977    0.3590147003    0.1310359142    0.2136755538
H.p         0.014649868     0.2244699001    0.1045631256    0.0292275757    -0.3108788731
DD.p.a      0.0487780571    0.4110431671    0.1248477568    0.031520474     -0.165063634
UD.p.a      -0.0860469341   0.2827301025    0.0202846312    0.0346531276    0.1120635299
H.a         0.0368490219    0.309237957     0.1632391981    0.0237391554    0.2661265612
DD.a.d      0.0091409683    0.8997330666    0.1370999474    0.0727023712    0.4532116425
UD.a.d      -0.136605978    0.8193969727    -0.0261392508   0.0699080761    0.3809565757
H.d         0.0491299629    0.2327241898    0.1319820036    0.0214662628    -0.2731609313
DD.d.n      0.0014250278    1.7162079811    0.1622196119    0.1029106721    0.06881187
UD.d.n      -0.1085469723   1.5872788429    0.0302376083    0.1028985615    0.1258056473
H.n         0.0156149864    0.1764760017    0.0856937777    0.0221133703    -0.3096122296
DD.n.Return 0.1869289875    1.3461661339    0.380603915     0.1941964377    0.3552833119
UD.n.Return 0.1093020439    1.2817270756    0.2949101374    0.1951615657    0.3886078856
H.Return    0.0028009415    0.1982381344    0.1013235123    0.0298796742    -0.6287328114
