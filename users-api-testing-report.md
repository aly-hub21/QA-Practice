API Testing Report - Users Endpoint
Website: jsonplaceholder.typicode.com
Tool: Postman

Test 1 - GET All Users
URL: /users
Expected: All users returned
Actual: 200 OK - 10 users returned
Pass/Fail: Pass

Test 2 - GET Single User
URL: /users/1
Expected: Single user data returned
Actual: 200 OK - Leanne Graham data returned
Pass/Fail: Pass

Test 3 - Unauthorized API (reqres.in)
URL: /api/users
Expected: Users data
Actual: 401 Unauthorized - API key required
Pass/Fail: Pass (expected behavior)
