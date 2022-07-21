# S3 Storage - SRIN Take-Home Assignments

**Write down as answer for every command used and result in each S3 operation below and explain your answer.**

**Bucket operation:**

- **Create bucket:** The appropriate command for this operation is ****`create-bucket`.** When we create a bucket, we need to define a bucket name and its region. This produces a bucket where objects are contained.
- **Delete bucket:**  If we delete a bucket, another user can use the previous bucket name. This is because buckets’ names have to be unique. Deleting a bucket will also delete all objects contained inside the bucket.
- **List all bucket**s**:** The appropriate command for this operation is ****`list-buckets`****. Returns a list of all buckets owned by the authenticated sender of the request.

**Object operation:**

- **Create object: `put-object`** adds an object to a bucket. User needs to have write permission to do this command.
- **Update object:** Updating a currently existing object is just the same as creating it for the first time, we just have to do the same put operation and it will overwrite the existing one.
- **Delete object: `delete-object`** removes an object, and also removes the null version of the object if it exists.
- **List objects in specified buckets and sub-buckets: `list-objects`** lists up to 1000 objects within a bucket.
****
