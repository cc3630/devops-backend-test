# devops-backend-test

后端测试工程，配合 cc-devops-test 使用

### 测试方法

- 本地 Get http://localhost:9527/v0/pets
- 线上(使用 rewrite 重定向) Get domain/petstore/v0/pets

`
token

{
"user": "5cb9a4edc48ad400120d28b0",
"exp": 2557035258,
"roles": [
  "OWNER"
]
}

eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoiNWNiOWE0ZWRjNDhhZDQwMDEyMGQyOGIwIiwiZXhwIjoyNTU3MDM1MjU4LCJyb2xlcyI6WyJPV05FUiJdfQ.GI1j9lxnvGkIZ5rMIS60PZOkre_RW4s0rwHEfJqRxKTeslYCpDdGV2rkNZsjMuuZLWZCu1RbytfJsJmc5x0erSQBBhRIiuLHgpaKvchAdMBoqLySlEy6HcD-STiQn-3rVO1IV71CCP_E3Hcp-ovCtuZxc9qtdJJ0P2dnr5420fc
`
12313112312312