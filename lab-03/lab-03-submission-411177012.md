1. /health指令   
C:\Users\aldan>curl -i https://eqryezwld3.execute-api.ap-southeast-2.amazonaws.com/prod/health   
HTTP/1.1 200 OK   
Date: Sat, 25 Oct 2025 09:06:58 GMT   
Content-Type: application/json   
Content-Length: 15   
Connection: keep-alive   
x-amzn-RequestId: 7f6258b6-e30b-4950-8db0-ce81f4717ff6   
x-amz-apigw-id: S_vwBEwpSwMEmlw=   
X-Amzn-Trace-Id: Root=1-68fc9332-3b536bbe320f79c82422a3e0;Parent=47cf3294250f18f8;Sampled=0;Lineage=1:af86942c:0   

{"status":"ok"}   
   
2.GET/ student指令   
C:\Users\aldan>curl -s -H "Authorization: Bearer    eyJraWQiOiI0REZRNjRKakpVMGxDN0NQNlUrS2djTHNFaVkyMUhVbjFGY2E0ZUNKMjFRPSIsImFsZyI6IlJTMjU2In0.eyJzdWIiOiJhOWVlZTRkOC1lMDMxLTcwYzItNDI1Ny0zMTYzMDIwMzhhMTciLCJpc3MiOiJodHRwczpcL1wvY29nbml0by1pZHAuYXAtc291dGhlYXN0LTJcL2FwLXNvdXRoZWFzdC0yX3lNaFlFV3R0ZiIsInZlcnNpb24iOjIsImNsaWVudF9pZCI6IjJiYW4xMzgydnZ3MHVvYzI3N2dyZGJ2MWY4IiwiZXZlbnRfaWQiOiJmN2JkZjY2OS02N2M3LTQzZjYtYWYwMC1iMDdjOTM1ZWNjZGUiLCJ0b2tlbl91c2UiOiJhY2Nlc3MiLCJzY29wZSI6InN0dWRlbnQtYXBpXC9zdHVkZW50cy53cml0ZSBvcGVuaWQgc3R1ZGVudC1hcGlcL3N0dWRlbnRzLnJlYWQiLCJhdXRoX3RpbWUiOjE3NjEzODEyMzEsImV4cCI6MTc2MTM4NDgzMSwiaWF0IjoxNzYxMzgxMjMxLCJqdGkiOiI5ZjA1ZTc3ZC1iMTAxLTQ0OTgtYjkzZS0wMWU5OTE3MmZiMjUiLCJ1c2VybmFtZSI6ImE5ZWVlNGQ4LWUwMzEtNzBjMi00MjU3LTMxNjMwMjAzOGExNyJ9.Pas7QLHY1clZqcpD4apJK-sVQNmpYmVABcSbyx5LKYE52IK3JPllKdRpQLuoDquV4km3-ANeBHA0vMlaFP2S8CsH2XQZAHpvh8YLLKWGDjCL7B0Z7LPN3Js9N-HcpC-sj7nHoCFB6c0JLSYTZtXYNip3bfgFu-DLx9l_HI8CK_Kt3ropDz_gEtqv-7Yp9kD2PeNBfyGPBJ_ToZu5GMX7NpdQYhHsx4lcAhCyDorZdiGMnrBZRpWWhY2mIPZZ3Hji9NZhXgnfPqmFS0ywElRYfC8Cq99C496KNHGjLcMpaEh4v6Y43r0ZChwehbewlV-aIWmIxNASS4kVkJ6pusRhew" "https://eqryezwld3.execute-api.ap-southeast-2.amazonaws.com/prod/api/v1/students?limit=2" | jq   
{   
  "message": "Invalid key=value pair (missing equal-sign) in Authorization header (hashed with SHA-256 and encoded with Base64): 'e+nM4KNp/p4EpTOhPyADwRwzVjX18YW9XOCPAHYNj3Q='."   
}   

