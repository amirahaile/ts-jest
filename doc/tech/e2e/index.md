# e2e tests

## Preparing

The preparation of E2E test directory is done in `scripts/e2e.js`. Here is the process:

![Preparing E2E tests](https://www.plantuml.com/plantuml/svg/ZLExZjim4Epv5ODhpYw20wwqcmE2AzBT7qWqkR8OymMIEiTDlZrBoZBaWv6aKZ6SnywktdAHgKpEukaZKPJ9-2FUNzzHA9Vy91einEumUMq99N_xoS1U-508oHp78e2piHQ7oLYzFC21Xf08Af4iLRACX5b3aDUeT5PjCAkIYpY7T88swOjsJw_qyhlhAinebo_E6d_gkXxrcr42J7r8lnJ5Wk3n_GV8VveKl2DVyihmF1eUOiFHG5ADpTXoWYtpxrpH86cv1KYUm_XRa8MJk-wbhxutTS0Cs2puSxvMmgb9bP0kszg2nuQouMwtpMPtDh4sKz3xeAbpGK-MSZytmUesSs3Mv_bMhBcu_MnlXkgzKo5UCF206KCA3giWB3RtjCgqNm97gKxoIB11dHh_bdFjo8OQZehKiiZ6_GTxb1bgbFv8UfPe8YvyqiDHboS-EcwRpuvFQiDxKcRx6BnTMhkgwvjMLzl27VgtJF-dMQd-kTopv-xdDIR3vpD5ReU-zFHeXTUjyUTwaZfulaAnQocM2qCj_S8YkOGen1i_vp_r3m00 "Preparing E2E tests")


## Running

When a test-case needs to be run with a given template within tests, here is what's happening (in `e2e/__helpers__/test-case/runtime.ts`):

![Running a test case](https://www.plantuml.com/plantuml/svg/TLN1Zjem4BtdAwpsK50BA_K8KdUlUwhK7m3ZJ8WNnuviPm5Lss_l6yS92RGS88p7Cs_Ul9cyX2Xzx1eZFltghDNsAAI85A9GCj2d8XqNnKPvaf74sVcJABNV5jRXhzV7EXP2lCOlneW3uQYgo9EDeYMVugmu3boaBREjQGs7EiYWmxeWs3bMiVeXw3iz_TdjE0boxCArCTgUThkdtyEj3txCGJ-sHQ4hiQXb06RhIjerhkmC1KRul1In9YiMLmfBvD_aQ3F7BGvI8OOghWCmtvqkXQULpspOjX7QWWPZaaFbl22fwXj9gRG184SSIoA3quLrIwvILqoZQw-YqeonygwPN9lnYMJPIziROwXAICza8emc97KJ54Dh6C15KHl5Vbhgdc7YRDzATP97MXcdJkit5-p-reFYN2EhM8n5CeWUmv066PXE9bu74QniG-rYCiy9dr2U1CEMETTYl9uwHYewhr4pQXJvAfNPSrPgS9rNFHy1zbeEyRgsb96x1YGD6EbCsTlw8ceQylO1AcTAyibsem3FtBPSu1kIhfMpbJwkty93YUmrTn6uL7LMHUtiyuC_I57StBEEjMXbcXHSZVZTPeTxZf8Qt3cmyaOJNI9BoXwpPOIV_eoooqSilS7iWCWF3M8vJZepo2yddKfmJdtsoOASoh6U2R67-dynykTVWdpeIAe1tqcVjtKKMb9QPg1tCnHSS-VGOqqtEJdWre01WTVEdK8_sHU9OQCCx-Zb0VYyKnJ2OhaNhp-J5qzZFsS87oMtEao6Q9Cbbmk3A9oz1qSHEqjr8M897Be8W1SmQ6KpxCftT0bncVrf79o20qmc3nyNLscLYUUInZvz7TV61DXdP9FHRR3RaYieUvZuOIINd67Hw11udgOQIDjqKCwTRlfevydypgE68kic3Vlrcx1qDjUXANTkI6h105rqI4FDSZjhwD9IKbjoEepoSw0CTx8zlqiOSEZV8CDhOxQXRvBo53jliVf3Pn8pw4rR52zmmUlnBm00 "Running a test case")