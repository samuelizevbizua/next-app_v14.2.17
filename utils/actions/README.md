### Server Actions

This folder contains all the **server actions**. Essentially mutations
(updating, creating, deleting) that are happening within your database or
endpoint

**Use Case Example:** It should be used for functions that **FETCH DATA** from
the server or directly from the API routes.

**Important Notes:**

- Most of these files will have the "use server" tag at their top.
- These functions can be called in **client** components within onClick,
  onSubmit, etc... functions
