To generate a mixture for galaxies with a polar structure, the results from FieldGeneratorENG.ipynb on Mosenkov distributions are used (letter dated 31.10.23).
Mixtures train_ps_mixture_1.json and demo_ps_mixture_1.json 
The following 6 distributions are selected:
seed = 43
1. Host: m:14.6459, re:12.1343, n:2.4282, ellip:0.5643, theta:0.2497, x,y:169.5792,1104.5967
   PS:   m:15.5145, re:35.6115, n:0.3753, ellip:0.6171, phi:  1.8299, x,y:169.5792,1104.5967
2. Host: m:15.3349, re:21.0884, n:2.8875, ellip:0.3657, theta:1.6884, x,y:869.0617,960.0060
   PS:   m:16.5806, re:38.7243, n:0.1367, ellip:0.6728, phi:  1.3636, x,y:869.0617,960.0060
3. Host: m:15.8099, re:23.8373, n:3.3305, ellip:0.6577, theta:2.3626, x,y:1412.3314,1165.3431
   PS:   m:16.5118, re:56.9306, n:0.2731, ellip:0.7183, phi:  1.8003, x,y:1412.3314,1165.3431
4. Host: m:15.3796, re:18.0636, n:3.2888, ellip:0.6434, theta:1.5547, x,y:426.4485,719.7833
   PS:   m:16.5191, re:36.0852, n:0.4272, ellip:0.7889, phi:  1.6386, x,y:426.4485,719.7833
5. Host: m:15.0049, re:19.0159, n:1.8957, ellip:0.5949, theta:0.2873, x,y:317.3715,1192.6135
   PS:   m:15.9722, re:50.6093, n:0.3187, ellip:0.8480, phi:  1.3320, x,y:317.3715,1192.6135
6. Host: m:15.8888, re:21.8419, n:2.8510, ellip:0.6574, theta:2.2086, x,y:669.0482,637.6037
   PS:   m:16.7814, re:49.0815, n:0.2747, ellip:0.8724, phi:  1.9143, x,y:669.0482,637.6037
7. Host: m:15.7537, re:10.1330, n:2.7694, ellip:0.3702, theta:2.4923, x,y:1339.7406,273.8032
   PS:   m:16.4257, re:26.0114, n:0.3332, ellip:0.8429, phi:  1.6522, x,y:1339.7406,273.8032
   
The variations for mixtures values:
m, ps_m        : +- 0.2
re             : +- 1.0
ellip, ps_ellip: +- 0.02
ps_re          : +- 2.0
ps_phi         : +- 0.05

When generating disk galaxies, a one-component mixture is used, specified in train_disk_3.json and demo_disk_3.json
