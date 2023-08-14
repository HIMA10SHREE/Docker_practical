# Docker multistage:

I have a python application: I Will dockerise it without multistage and with multistage.

Multistaging reduces the size by  80%

1.Without multistage:

Dockerfile:

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/33900724-f656-4af7-a91b-bdd3b2c69c52)

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/c23fb4c8-60f3-41b0-80c8-20c95a23da92)


![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/acc8967f-52ec-4729-8d02-c0e326f1d9f3)

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/391d9cf8-31da-49c7-9474-56634e913727)

Without multistage it is 473 mb

Lets see with multistage:

Dockerfile:
![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/1ec348a0-2bfc-4ef7-9a27-83249c9f21da)

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/78ec9c03-1170-4c0c-9f36-f459e5e2799b)

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/420e47cf-785e-4046-b6ad-ae891934a590)

![image](https://github.com/HIMA10SHREE/Docker_practical/assets/52618743/388028af-d892-463e-9a42-fe290eadc385)


Size reduced to 56 mb


