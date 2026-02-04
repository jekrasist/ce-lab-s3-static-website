# Lab Solution: Host a Static Website on Amazon S3

**Student Name:** ____Ahmet Erdogan_______________________  
**Date:** ____________________04.02.2026_______  
**Lab Completion Time:** _________~70__ minutes

---

## Part 1: Bucket Configuration

### Bucket Information

**Bucket Name:** ___________my-static-website-ae-2026________________

**Region:** ___________us-east-1________________

**Bucket Website Endpoint URL:**
```
________________http://my-static-website-ae-2026.s3-website-us-east-1.amazonaws.com___________________________________________
```

**Screenshot 1: Bucket Creation Confirmation**
![Bucket Created](<img width="1078" height="97" alt="image" src="https://github.com/user-attachments/assets/12526d27-47b5-4e2f-8fa0-d851fb75f36d" />
)

---

## Part 2: Static Website Hosting Configuration

### Configuration Details

**Index Document:** ___________________________

**Error Document:** ___________________________

**Screenshot 2: Static Website Hosting Settings**
![Static Hosting Config](<img width="1346" height="313" alt="image" src="https://github.com/user-attachments/assets/77cbfc21-8fed-4670-ac5c-be1e29352fea" />
)

---

## Part 3: Website Files

### Files Created

List the files you created:
1. ____error.html_______________________
2. ___________styles.css________________
3. ______________index.html_____________

**Did you customize the HTML/CSS?** (Yes/No): __no____

**If yes, describe your customizations:**
```
_____________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

**Screenshot 3: Files Uploaded to S3**
![Files in S3](<img width="1600" height="500" alt="image" src="https://github.com/user-attachments/assets/2e24582d-ac35-47e0-83ef-e14588f28e21" />
)

---

## Part 4: Bucket Policy

### Bucket Policy Applied

**Paste your complete bucket policy here:**
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      
      
      
      
    }
  ]
}
```

**Screenshot 4: Bucket Policy Configuration**
![Bucket Policy](<img width="1600" height="530" alt="image" src="https://github.com/user-attachments/assets/fc5f5023-9caf-4e8c-a8ac-7eafa29a505b" />
)

---

## Part 5: Testing and Verification

### Website Testing

**Website URL (from endpoint):**http://my-static-website-ae-2026.s3-website-us-east-1.amazonaws.com
```
___________________________________________________________
```

**Did the website load successfully?** (Yes/No): __yes____

**Did the CSS styling apply correctly?** (Yes/No): ___yes___

**Screenshot 5: Working Website**
![Website Live](<img width="1600" height="713" alt="image" src="https://github.com/user-attachments/assets/4002bc59-6888-4bfd-8dc5-f27f54827e96" />
)

### Error Page Testing

**Test URL used:**http://my-static-website-ae-2026.s3-website-us-east-1.amazonaws.com/html
```
___________________________________________________________
```

**Did custom error page display?** (Yes/No): ___yes___

**Screenshot 6: Custom 404 Error Page**
![Error Page](<img width="1600" height="279" alt="image" src="https://github.com/user-attachments/assets/c3883c23-a539-4060-bd22-a7c413ffaba1" />
)

---

## Part 6: CLI Commands Used

**Document all AWS CLI commands you executed:**

```bash
# Bucket creation


# Enable website hosting


# Upload files



# Apply bucket policy


# Verify configuration


```

---

## Bonus Challenges Completed

- [ ] Challenge 1: Added about.html page
- [ ] Challenge 2: Used subdirectories for organization
- [ ] Challenge 3: Used `aws s3 sync` command

**Bonus Challenge Notes:**
```
_____________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

---

## Reflection Questions

### 1. What are the advantages of S3 static hosting compared to traditional web servers?

**Your answer:**
```
____________No costs when idle, no expensive hardware needed and scalability_________________________________________________
_____________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

### 2. Why is a bucket policy necessary for public website access?

**Your answer:**
```
___To grant read only access__________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

### 3. What are the limitations of S3 static website hosting?

**Your answer:**
```
____________no database connection_________________________________________________
_____________________________________________________________
_____________________________________________________________
```

### 4. When would you NOT use S3 for website hosting?

**Your answer:**
```
___when I need advanced security.__________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

### 5. How does S3 static hosting fit into cost optimization strategies?

**Your answer:**
```
_____________No idle charges and less administrative headache.________________________________________________
_____________________________________________________________
_____________________________________________________________
```

---

## Troubleshooting Log

**Did you encounter any issues?** (Yes/No): __no____

**If yes, document the issues and how you resolved them:**

| Issue | Error Message | Solution | Time to Resolve |
|-------|--------------|----------|-----------------|
|       |              |          |                 |
|       |              |          |                 |
|       |              |          |                 |

---

## Cleanup Confirmation

- [ ] Emptied S3 bucket
- [ ] Deleted S3 bucket
- [ ] Verified no resources remain

**Cleanup CLI commands used:**
```bash
# Empty bucket


# Delete bucket


```

---

## Self-Assessment

**Rate your understanding of each concept (1-5, where 5 is expert):**

| Concept | Rating | Notes |
|---------|--------|-------|
| S3 bucket creation | ___/5 | |
| Static website hosting configuration | ___/5 | |
| Bucket policies and public access | ___/5 | |
| Uploading and managing S3 objects | ___/5 | |
| S3 website endpoints | ___/5 | |
| HTML/CSS basics | ___/5 | |

---

## Instructor Verification

**Instructor Name:** ___________________________

**Date Reviewed:** ___________________________

**Website URL Verified:** ☐ Yes ☐ No

**Comments:**
```
_____________________________________________________________
_____________________________________________________________
_____________________________________________________________
```

**Grade/Status:** ___________________________

---

## Additional Resources Referenced

List any documentation, tutorials, or resources you used:

1. ___________________________________________________________
2. ___________________________________________________________
3. ___________________________________________________________

---

**Lab Status:** ☐ Complete ☐ Needs Revision

**Total Time Spent:** ________ minutes

**Submission Date:** ___________________________
