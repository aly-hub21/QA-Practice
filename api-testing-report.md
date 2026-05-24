API Testing Report
Website: jsonplaceholder.typicode.com
Tool: Postman

Test 1 - GET Single Post
URL: /posts/1
Expected: Post data returned
Actual: 200 OK - userId, id, title, body returned
Pass/Fail: Pass

Test 2 - GET All Posts
URL: /posts
Expected: All posts returned
Actual: 200 OK - 100 posts returned
Pass/Fail: Pass

Test 3 - GET Invalid Post
URL: /posts/999
Expected: Error message
Actual: 404 Not Found
Pass/Fail: Pass

Test 4 - POST New Post
URL: /posts
Expected: New post created
Actual: 201 Created - id 101 returned
Pass/Fail: Pass

Test 5 - PUT Update Post
URL: /posts/1
Expected: Post updated
Actual: 200 OK - Updated Title returned
Pass/Fail: Pass

Test 6 - DELETE Post
URL: /posts/1
Expected: Post deleted
Actual: 200 OK - Empty response
Pass/Fail: Pass

Overall: All API tests passed
