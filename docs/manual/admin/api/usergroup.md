!!! tip "/api/v1/users/groups/{id}/"
    === "POST"
        ## 创建用户组
        | 参数名 | 类型     | 描述     | 是否必选 | 可选值 |
        |--------|----------|----------|----------|--------|
        | name   | String   | 名称     | 是       | -      |
        | users  | String[] | 用户     | 否       | -      |

        !!! tip "请求示例"
            ```sh
            curl -X POST 'https://localhost/api/v1/users/groups/cdd61c0e-2012-416a-bde3-f2c642ded82a/' \
                -H 'Authorization: Bearer b96810faac725563304dada8c323c4fa061863d4' \ 
                -H 'X-JMS-ORG: 00000000-0000-0000-0000-000000000002'
            ```
    === "DELETE"
        ## 删除用户组
        !!! tip "请求示例"
            ```sh
            curl -X DELETE 'https://localhost/api/v1/users/groups/7413d36d-cf37-45f4-b42a-cd5eeff1f4ff/' \ 
                -H 'Content-Type:application/json' \ 
                -H 'Authorization: Bearer b96810faac725563304dada8c323c4fa061863d4' \ 
                -H 'X-JMS-ORG: 00000000-0000-0000-0000-000000000002'
            ```
