# fake-op
Fake OpenID Provider

## Private key
Use this private key to mint your ID tokens:

```json
{
  "d": "TvviRuovSHR93xA65HVKjUD1Qpi2rmvXktc-mjKbMKnHWFArwe_d8O11CsD8gndRtpF3RVRaTI9XCuUH7fdDMy6QuYXhr9BAwUO7FnfLZ1NcQkWzmf9Cd9QKCE5KL0ODMAoj4UcxnvywyHbBMLfNSJGbKzj6PfjjqWVwx07EHVKYKCLKmnJWJzYFVSkWEKbW2N6yZ3KV9WbFscSfL4gJ0ULWQdNYLXh0BHzOSkMm9X1MZiHrAPQckVwufyFu4IbCahYiLAeCy_0Xd2ZrN9JVpVSGY1QAflKMU1SH-IEZao4YuSAeN67jtsl9JX0_-rtzGTtUz6MdnUwjz0BCuApW1Q",
  "dp": "hq1ZFspT4cE2Zpv0lArrw6RG-YGQ0YO9H_NCmnBS4TjXDQX3LTVLsYKWzmQ1LfXCrqcNWARZwbry1_pgXcPo7CIwCWCZ1zc39byttQv6aKYXsJIB1Zw4VW4jJii25VV52uEP6ps8V1lHanxlIVkCCNdoWL63LUW1F5BxRO6z7SU",
  "dq": "kkxR72QSc5Z6ByJBlsB_uE8NYJLwsmZTi-2qUC0tM5yHofHhFsLLiT-RI1EX2ZMiVnGMuJmecnh44BpGBpaNFTiJNZyvH19Dulkzczq-h186dwrflCsmZ0ti1atkl1sVQl2JlY08dJLAYHXun0PJomJV24EEFbl6tG1dddGS5_0",
  "e": "AQAB",
  "kty": "RSA",
  "n": "xDRkJZhwALw60VUc6v-vStolrIpw7fOvs4aV6_5dJ7_rN1kuB3VRWy6PvRDzFZVj9WBjHkabqT-Cf5wy5PGlOp7uXWuoC5_EZaNdc1advVrQoRhyTZtBDDAC1jSqRV3ex-mkgEAl8SqhMcTkqk3om9Nrhs5ReCJdq3IPcgPxlOXeQFDcS-YnwYTP9P3q2wn5eoGPrTwu32FJvEeOfXy2s53ggotITX7EB9ph166hL1DbBOP6lMmTPUYInq8qeF40xCU1tbLhCqnMhGZI6gZPVs6u615zLuscFBS7zNUk8BaJvlOWluJCSQDdrGABz2AzN0du-VbHSvWtYjq6hT1FPw",
  "p": "_yQB3ai6VffNQ26-idiKhQ352zXnqV0KBHj3cXcyOow4OaPEK9eDX35K_D-MkvVsLZj9fesV56xxJ6EacvhtZ1-Jcl3ExJ1KfysjfS2gCi-wXV9gNq_1thOC0lcXrkaXWZuG5uCwjnqvWgdO-OWbSHzN9iLW1ySeV7Ak3OD4YHM",
  "q": "xN2RHvx434wC6PPQd4TzipvWruFjcQBJ7-lTS-ou0TOI107bHptr2vLTCVzevG9O2SkFe7BfLrUerzCNtzk-w866r290SVlhJq0EVrhkN9pKQ1ylfGKEe75u10e-yy1e6-i-4oLMjhtDsUBBCbCKCwx2zZyp0MZQVmote_HlUQU",
  "qi": "JZo3Ym9ZOiAIb0BQgdLhtGl7d2nyVyAMS0Hd0Le9cXO26L1nxgBD8vIpBmS9kncub1UME61HS7BucITFt19UyoTL9zeJjlVOq3ghRsGd1hHiUXhwfg2i5FcaUQbLpbH5IqA8a4KSFNtxjgXZohcdvyn4_Z2ctOuzs_WtG5uuKBc"
}
```

Set the following header:

```json
{
  "alg": "RS256",
  "kid": "nevergonnagiveyouup"
}
```

Set the following claims:

```json
{
  "iss": "https://fake-openid-provider.netlify.app"
}
```
