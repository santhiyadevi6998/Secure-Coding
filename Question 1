# Secure Coding Challenges

This repository contains a set of coding challenges focused on **secure coding** practices to help developers learn how to prevent common security vulnerabilities.

## Challenges

### 1. **SQL Injection Prevention (C#)**

**Question:**  
Fill in the blank to securely fetch a user's information from the database using a parameterized query. Assume the username is taken from user input.

```csharp
using (SqlConnection connection = new SqlConnection(connectionString))
{
    string query = "SELECT * FROM Users WHERE Username = @__________";  // Fill in the blank
    SqlCommand cmd = new SqlCommand(query, connection);
    cmd.Parameters.AddWithValue("@__________", username);  // Fill in the blank
    connection.Open();
    SqlDataReader reader = cmd.ExecuteReader();
    while (reader.Read())
    {
        // Process data
    }
}# Secure-Coding
