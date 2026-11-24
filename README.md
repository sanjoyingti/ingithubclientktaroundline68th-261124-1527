# ingithubclientktaroundline68th-261124-1527
Built by Arin: In GitHubClient.kt (around line 68, the callOnce function that throws ProviderException("GitHub: Not Found")): when a request to api.github.com returns HTTP 404, do not immediately throw. Instead: (1) capture the requested URL path (strip any token/query params) and the response's X-O
