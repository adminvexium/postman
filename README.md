# Postman  

Practical cases 1-5. Please check the following details:  

<br>

### 0- Configuration  
- Import **global**, **environment**, and **collection** `.JSON` files into Postman.  
- Authorization set at **collection level**:  
  - Auth Type: **API Key**  
  - Key: `"api key"`  
  - Value: `"special-key"`  
  - Add to: **Header**

<br>

### Case 1  
- **Headers**:  
  - `Content-Type`: `application/json`  
- **Body**:  
  - Manually added `"id"` and `"username"`  
  - Other fields (`firstName`, `lastName`, `email`, etc.) stored as **variables**  
- **Scripts**:  
  - Added **Pre-request** script  

<br>

### Case 2  
- Verified the created user using the **global variable**  

<br>

### Case 3  
- Saved all the **status types** (e.g., `0`, `1`, and `2`) for reference  

<br>

### Case 4  
- **Headers**:  
  - `Content-Type`: `application/json`  
- Updated user details as required (fixed the email in a second step).  

<br>

### Case 5  
- **Tests**:  
  - Added 9 **post-request tests**, including:  
    - Status code verification  
    - Response body structure validation  
    - Data integrity checks (e.g., fields match expected values)  

<br>

### Examples  
- Examples have been saved per step in the **Postman collection** for reference.
