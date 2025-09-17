![WhatsApp Image 2025-09-13 at 16 32 45_2bf6130a](https://github.com/user-attachments/assets/5116cf53-b849-49d4-816e-7c79a5573d29)


Testing the API – Create Student

This screenshot shows the successful execution of the POST /api/students endpoint using Postman. Here, a new student record is being added to the MongoDB database.

The request is sent to http://localhost:3000/api/students with the following JSON payload:

{
  "name": "Mahesh",
  "age": 20,
  "major": "Computer Science"
}


The response confirms that the student was successfully created with a 201 Created status.

The response body includes the stored student information along with the generated _id, timestamp (createdAt), and versioning field (__v) managed by Mongoose.

This validates that the Node.js Express server is connected to MongoDB and is able to perform Create (POST) operations through the API.
