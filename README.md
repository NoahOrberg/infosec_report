# Infomation Security Report
### RSA-REPORT(rsa-report)
#### DEMO
![demo](./img/rsa-report_demo.gif)
#### Build

```
% cd rsa-report/
% stack build
```

#### Execute
##### STEP 1.
```
% stack exec rsa-report-exe
input number ["p", "q"] ->
{P,Q NUM}
```

- Input p,q number in {P, Q NUM}.

##### STEP 2.
```
Please select e-number : [11,13,17,19,23,29,31,37,41,43,47,53,59,61,67,71,73,79,83,89,97,101,103,107,109,113,121,127,131,137,139,143,149,151,157,163,167,169,173,179,181,187,191,193,197,199,209,211,221,223,227,229,233,239,241,247,251,253,257,263,269,271,277,281,283,289,293,299,307,311,313,317,319,323,331,337,341,347,349,353,359,361,367,373,377,379,383,389,391,397,401,403,407,409,419,421,431,433,437,439,443,449,451,457,461,463,467,473,479,481,487,491,493,499,503,509,517,521,523,527,529,533,541,547,551,557,559,563,569,571,577,583,587,589,593,599,601,607,611,613,617,619,629,631,641,643,647,649,653,659,661,667,671,673,677,683,689,691,697,701,703,709,713,719,727,731,733,737,739,743,751,757,761,767,769,773,779,781,787,793,797,799,803,809,811,817,821,823,827,829,839,841,851,853,857,859,863,869,871,877,881,883,887,893,899,901,907,911,913,919,923,929,937,941,943,947,949,953,961,967,971,977,979,983,989,991,997,1003,1007,1009,1013,1019,1021,1027,1031,1033,1037,1039,1049,1051,1061,1063,1067,1069,1073,1079,1081,1087,1091,1093,1097,1103,1109,1111,1117,1121,1123,1129,1133,1139,1147,1151,1153,1157,1159,1163,1171,1177,1181,1187,1189,1193,1199,1201,1207,1213,1217,1219,1223,1229,1231,1237,1241,1243,1247,1249,1259,1261,1271,1273,1277,1279,1283,1289,1291,1297,1301,1303,1307,1313,1319,1321,1327,1331,1333,1339,1343,1349,1357,1361,1363,1367,1369,1373,1381,1387,1391,1397,1399,1403,1409,1411,1417,1423,1427,1429,1433,1439,1441,1447,1451,1453,1457,1459,1469,1471,1481,1483,1487,1489,1493,1499,1501,1507,1511,1513,1517,1523,1529,1531,1537,1541,1543,1549,1553,1559,1567,1571,1573,1577,1579,1583,1591,1597,1601,1607,1609,1613,1619,1621,1627,1633,1637,1639,1643,1649,1651,1657,1661,1663,1667,1669,1679]
{E NUM}
```

- Enter a number in the above list in {E NUM}.

#### Result format
```
public_key is ({n}, {e}), Secret_key is {d}
```
