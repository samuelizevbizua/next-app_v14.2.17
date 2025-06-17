### Data Access Layer

This folder is the **data access layer** that contains functions that are called
**ONLY** on the server and can only be called on either a server component or in
an API route.

**Use Case Example:** It should be used for functions that **FETCH DATA** from
the server or directly from the API routes.

**Important Notes:**

- Most of these files will have the "use server" tag at their top.
- Data fetching with these functions is recommended to be used on server
  components via async/await.
