# Bonus Post-Book API 

This is the bonus exercise for when you're ready with the frontend and backend. 
This is optional. 

## Bonus Task - Making requests to the backend. 

  1. Make a GET request to  `/post/posts/:id` which gets the post by id and show the details in a detail component in react. 

  2. Make a DELETE request to `/post/posts/delete/:id` which deletes the post by ID when clicking a button. 
     
  3. Make a PUT request to `/post/posts/update/:id` which allows you to update an existing post using the body: 
     ```json
      {
          "title":"My title",
          "content":"The content of my updated post"
      }
     ```

