# dockerizenodeapp

C:\intro-to-docker-main\01-Basics\Labs\01-NodeApp\blog-shop>docker build . -t cliff/node-web-app
[+] Building 198.5s (7/9)
 => [internal] load build definition from Dockerfile                                                                                 0.0s
 => => transferring dockerfile: 445B                                                                                                 0.0s
 => [internal] load .dockerignore                                                                                                    0.1s
 => => transferring context: 34B                                                                                                     0.0s
 => [internal] load metadata for docker.io/library/node:14                                                                           2.0s
 => [1/5] FROM docker.io/library/node:14@sha256:2f39686f6d0b2687550659367fa11f56018a0f782b7e30f1a0ea56b11dece124                   146.6s
 => => resolve docker.io/library/node:14@sha256:2f39686f6d0b2687550659367fa11f56018a0f782b7e30f1a0ea56b11dece124                     0.0s
 => => sha256:ffa46b3d4cf7317e0eb42cc80535e2bfee48d57f6fe28a8e84a506725cbaad8f 2.21kB / 2.21kB                                       0.0s
 => => sha256:531acaaca10c6b6bdcad5799002b0e81ca8f5c7a7c8a99bd809ed07c75bad281 7.68kB / 7.68kB                                       0.0s
 => => sha256:9bed1e86f01ee95c76d2c8b4385a47ae336e6d293afade9368469d99daa9369f 11.30MB / 11.30MB                                    14.4s
 => => sha256:2f39686f6d0b2687550659367fa11f56018a0f782b7e30f1a0ea56b11dece124 776B / 776B                                           0.0s
 => => sha256:f5196cdf25181bc7e4411865a2e002932b7b6b0ffce787c04c1bdeaf1f204f20 45.43MB / 45.43MB                                    44.1s
 => => sha256:f44e4bdb3a6c1325cc4d40e585ed7a759127c0c87b0388ec0236b1698827d70d 4.34MB / 4.34MB                                       4.9s
 => => sha256:2f75d131f4060950dd6cc1f580e2fa5504ece8d692113a9cdb0a866637b397d7 49.77MB / 49.77MB                                    47.8s
 => => sha256:07dff4ad21ebdb3ce3e329699663b2f81af70152453025f6624584a39a8e22b6 214.48MB / 214.48MB                                 126.4s
 => => sha256:e0ac4f13b766d321acc3b650d3d23b82828995711f6f247ff591722c00d04cec 4.19kB / 4.19kB                                      44.4s
 => => extracting sha256:f5196cdf25181bc7e4411865a2e002932b7b6b0ffce787c04c1bdeaf1f204f20                                            9.2s
 => => sha256:8446d83fe25107efdfd0b5a8d98825a7981c07e4e0d48186fd203a7702259cbe 35.62MB / 35.62MB                                    73.2s
 => => sha256:fe9dc73ac9f524074f091bac497f07a2190f2e51d31dbc98f633fcc1a5a73271 2.34MB / 2.34MB                                      50.4s
 => => sha256:428a7d50970955e9ab76ffa4c91cf71c7132b795ef00d8e65ff6c0ce290ed432 458B / 458B                                          50.6s
 => => extracting sha256:9bed1e86f01ee95c76d2c8b4385a47ae336e6d293afade9368469d99daa9369f                                            2.4s
 => => extracting sha256:f44e4bdb3a6c1325cc4d40e585ed7a759127c0c87b0388ec0236b1698827d70d                                            0.7s
 => => extracting sha256:2f75d131f4060950dd6cc1f580e2fa5504ece8d692113a9cdb0a866637b397d7                                           14.9s
 => => extracting sha256:07dff4ad21ebdb3ce3e329699663b2f81af70152453025f6624584a39a8e22b6                                           15.6s
 => => extracting sha256:e0ac4f13b766d321acc3b650d3d23b82828995711f6f247ff591722c00d04cec                                            0.1s
 => => extracting sha256:8446d83fe25107efdfd0b5a8d98825a7981c07e4e0d48186fd203a7702259cbe                                            3.3s
 => => extracting sha256:fe9dc73ac9f524074f091bac497f07a2190f2e51d31dbc98f633fcc1a5a73271                                            0.2s
 => => extracting sha256:428a7d50970955e9ab76ffa4c91cf71c7132b795ef00d8e65ff6c0ce290ed432                                            0.0s
 => [internal] load build context                                                                                                  117.1s
 => => transferring context: 551.24MB                                                                                              116.9s
 => [2/5] WORKDIR /usr/src/app                                                                                                       1.2s
 => [3/5] COPY package*.json ./                                                                                                      0.3s
 => [4/5] RUN npm install                                                                                                           48.0s


