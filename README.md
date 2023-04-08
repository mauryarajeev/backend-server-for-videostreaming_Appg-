# backend-server-for-videostreaming_Appg-
How to start backend server of this app
   step 1> clone this repo
   step 2> npm install run command in terminal
   step 3> set up all string in dot env 
           a> mongoDb database url
           b> jwt key url
   step 4> nodemon index.js run in terminal
   step 5> check all endpoint in via postman or Insomnia frontend client 
   see here ---->
   
   {
    "_type": "export",
    "__export_format": 4,
    "__export_date": "2023-04-08T12:29:05.247Z",
    "__export_source": "insomnia.desktop.app:v2023.1.0",
    "resources": [
        {
            "_id": "req_1a620518577e478588ef6797a0b311a3",
            "parentId": "fld_75d983be2d4b4fb6a1ab4d82d3e7a76a",
            "modified": 1679059357901,
            "created": 1677693176659,
            "url": "localhost:8800/api/comments/63ff87c8c92597f84a0905f1",
            "name": "get all comment on video",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 0,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "fld_75d983be2d4b4fb6a1ab4d82d3e7a76a",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357817,
            "created": 1677692761298,
            "name": "comment",
            "description": "",
            "environment": {},
            "environmentPropertyOrder": null,
            "metaSortKey": 0,
            "_type": "request_group"
        },
        {
            "_id": "wrk_e72f26384b25403daaefe18e001bb244",
            "parentId": null,
            "modified": 1677687717724,
            "created": 1677687647543,
            "name": "videoApp",
            "description": "",
            "scope": "design",
            "_type": "workspace"
        },
        {
            "_id": "req_87c3af1df70641b2afe41bb4bcf7eee0",
            "parentId": "fld_75d983be2d4b4fb6a1ab4d82d3e7a76a",
            "modified": 1679059357901,
            "created": 1677692763556,
            "url": "localhost:8800/api/comments",
            "name": "add comment",
            "description": "",
            "method": "POST",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"desc\":\"first comments\",\n\t\"videoId\":\"63ff87c8c92597f84a0905f1\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 100,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_39cc0e3298754a1ab5c5c1ee69236cbf",
            "parentId": "fld_48b202952b78462982642745b6eeddf1",
            "modified": 1679059357901,
            "created": 1677691967754,
            "url": "",
            "name": "New Request",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 0,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "fld_48b202952b78462982642745b6eeddf1",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357818,
            "created": 1677691960293,
            "name": "sub channel",
            "description": "",
            "environment": {},
            "environmentPropertyOrder": null,
            "metaSortKey": 100,
            "_type": "request_group"
        },
        {
            "_id": "req_4135105ebcd542a58c162d070f60a398",
            "parentId": "fld_7db129acce6e41a5b13c19faf93ba277",
            "modified": 1679059357903,
            "created": 1677693532712,
            "url": "localhost:8800/api/videos/find/63ff8bfec92597f84a0905f5",
            "name": "video find",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 0,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "fld_7db129acce6e41a5b13c19faf93ba277",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357818,
            "created": 1677691389797,
            "name": "video",
            "description": "",
            "environment": {},
            "environmentPropertyOrder": null,
            "metaSortKey": 200,
            "_type": "request_group"
        },
        {
            "_id": "req_c918296206c7471aa3fcb1150c1f6331",
            "parentId": "fld_7db129acce6e41a5b13c19faf93ba277",
            "modified": 1679059357903,
            "created": 1677692468491,
            "url": "localhost:8800/api/videos/tags?tags=js,py,c",
            "name": "get by tag",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 100,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_75d1940f5dc44dc799fc1afae820f5a4",
            "parentId": "fld_7db129acce6e41a5b13c19faf93ba277",
            "modified": 1679059357903,
            "created": 1677692347018,
            "url": "localhost:8800/api/videos/random",
            "name": "get random video",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 200,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_47117a9311044c07833002009f47f1ae",
            "parentId": "fld_7db129acce6e41a5b13c19faf93ba277",
            "modified": 1679059357903,
            "created": 1677692221479,
            "url": "localhost:8800/api/videos/sub",
            "name": "get subcribed video",
            "description": "",
            "method": "GET",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 300,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_d2f4e4e47c704f4ebab19b14ab1b0941",
            "parentId": "fld_7db129acce6e41a5b13c19faf93ba277",
            "modified": 1679059357903,
            "created": 1677691409201,
            "url": "localhost:8800/api/videos",
            "name": "Add video",
            "description": "",
            "method": "POST",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"title\":\"the best video\",\n\t\"desc\":\"test disc\",\n\t\"imgUrl\":\"test\",\n\t\"videoUrl\":\"test\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 400,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_61d960ba9835442692e5e844db2b7eab",
            "parentId": "fld_a51ed7f4d4434978bba43aada5630afe",
            "modified": 1679059357904,
            "created": 1677693381009,
            "url": "localhost:8800/api/users/like/63ff87c8c92597f84a0905f1",
            "name": "like",
            "description": "",
            "method": "PUT",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 0,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "fld_a51ed7f4d4434978bba43aada5630afe",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357818,
            "created": 1677690145405,
            "name": "user/creator",
            "description": "",
            "environment": {},
            "environmentPropertyOrder": null,
            "metaSortKey": 300,
            "_type": "request_group"
        },
        {
            "_id": "req_ae670963e39a466483e0b342993c12b4",
            "parentId": "fld_a51ed7f4d4434978bba43aada5630afe",
            "modified": 1679059357904,
            "created": 1677692016689,
            "url": "localhost:8800/api/users/sub/63ff87c8c92597f84a0905f1",
            "name": "sub channel",
            "description": "",
            "method": "PUT",
            "body": {},
            "parameters": [],
            "headers": [],
            "authentication": {},
            "metaSortKey": 100,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_5ed6edb8ac03438e88500b1634d69ac2",
            "parentId": "fld_a51ed7f4d4434978bba43aada5630afe",
            "modified": 1679059357904,
            "created": 1677690593237,
            "url": "localhost:8800/api/users/63ff826ec92597f84a0905d8",
            "name": "delete user",
            "description": "",
            "method": "PUT",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"name\":\"update user again\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 200,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_9d567d2a85b14a2e9149759ab19c97c8",
            "parentId": "fld_a51ed7f4d4434978bba43aada5630afe",
            "modified": 1679059357904,
            "created": 1677690158324,
            "url": "localhost:8800/api/users/63ff87c8c92597f84a0905f1",
            "name": "Update user",
            "description": "",
            "method": "PUT",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"name\":\"user update2\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 300,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_9cc56d720029482fadd586f7c7e0935d",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357818,
            "created": 1677689495596,
            "url": "localhost:8800/api/auth/signin",
            "name": "signin",
            "description": "",
            "method": "POST",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"name\":\"test2\",\n\t\"password\":\"123456789\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 400,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "req_89e7efa2d0ae4eeca8e3094e6bf404e7",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1679059357819,
            "created": 1677687647576,
            "url": "localhost:8800/api/auth/signup",
            "name": "signup",
            "description": "",
            "method": "POST",
            "body": {
                "mimeType": "application/json",
                "text": "{\n\t\"name\":\"test2\",\n\t\"email\":\"test2@gmail.com\",\n\t\"password\":\"123456789\"\n}"
            },
            "parameters": [],
            "headers": [
                {
                    "name": "Content-Type",
                    "value": "application/json"
                }
            ],
            "authentication": {},
            "metaSortKey": 500,
            "isPrivate": false,
            "settingStoreCookies": true,
            "settingSendCookies": true,
            "settingDisableRenderRequestBody": false,
            "settingEncodeUrl": true,
            "settingRebuildPath": true,
            "settingFollowRedirects": "global",
            "_type": "request"
        },
        {
            "_id": "env_2c1ff10ad71ee51fed971c5b8a7912da4fa58d24",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1677687647564,
            "created": 1677687647564,
            "name": "Base Environment",
            "data": {},
            "dataPropertyOrder": null,
            "color": null,
            "isPrivate": false,
            "metaSortKey": 1677687647564,
            "_type": "environment"
        },
        {
            "_id": "jar_2c1ff10ad71ee51fed971c5b8a7912da4fa58d24",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1677690840666,
            "created": 1677687647568,
            "name": "Default Jar",
            "cookies": [
                {
                    "key": "access_token",
                    "value": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZmY4N2M4YzkyNTk3Zjg0YTA5MDVmMSIsImlhdCI6MTY3NzY5MDg0MH0.H_aKX2-z2bvofUQGeGNUUGdSJ8v9g4R7Cw2sw-DmL2s",
                    "domain": "localhost",
                    "path": "/",
                    "httpOnly": true,
                    "hostOnly": true,
                    "creation": "2023-03-01T16:59:42.396Z",
                    "lastAccessed": "2023-03-01T17:14:00.665Z",
                    "id": "6854809778601627"
                }
            ],
            "_type": "cookie_jar"
        },
        {
            "_id": "spc_91f7d12a93fc46119ff4d5629be6d39e",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1677687717721,
            "created": 1677687647544,
            "fileName": "videoApp",
            "contents": "",
            "contentType": "yaml",
            "_type": "api_spec"
        },
        {
            "_id": "uts_d3149bc541fe4932a9ab7f8517197d1f",
            "parentId": "wrk_e72f26384b25403daaefe18e001bb244",
            "modified": 1677687647580,
            "created": 1677687647580,
            "name": "Example Test Suite",
            "_type": "unit_test_suite"
        },
        {
            "_id": "ut_1bff14e4a5ef4e2fa2bec963839ea768",
            "parentId": "uts_d3149bc541fe4932a9ab7f8517197d1f",
            "modified": 1677687923931,
            "created": 1677687923931,
            "requestId": null,
            "name": "Returns 200",
            "code": "const response1 = await insomnia.send();\nexpect(response1.status).to.equal(200);",
            "_type": "unit_test"
        }
    ]
}
   
   
