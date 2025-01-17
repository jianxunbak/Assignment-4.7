## Assignment

### Brief

In this assignment, we will explore other aspects of secret management. Spend some time to read this [blog](https://blog.gitguardian.com/secrets-api-management/) and answer the questions below.

| Question | Answer |
| -------- | ------ |

|1. Never store secret in git. Why?
|
a. Private repositories are high value targets for hackers as it is common for people to keep secrets in there
b. Repositories can get forked, cloned into new machines and the secrets, the repo history, will be accessile.
|
|2. How can you ensure no secret is being stored accidentally on git?

|
a. By using .gitIgnore to specificaly exclude sensitive data from being stagged and commited.
b. By not using git add . or git add \* and manually add files into stagging area.
|

|3. Name at least two "Secret as a Service" provider
|
a. Hashicorp Vault
b. AWS Key Management Service
|
|4. Based on the pros and cons, would you use such service? Give your reason.
|
a. Yes. Such services provides a secure platform to manage secrets and prevents it from spreding unintentionally if the company budget, team experience, company's infrastructure and project type allows for it.
b. Adopting such a service is highly dependent on the company's budget and existing infrastructure as the company may not be able to host it.
c. The team's experience and comfort level must be considered as such services can be complex and may have a steep learning curve.
c. The selected project to implement these services as it could mean a considerable amount of resources is required to refactor and retest existing code if the project is already in advance stages of development/testing
|

### Challenge (Optional)

Read about how to [detect hardcoded secrets](https://circleci.com/blog/detect-hardcoded-secrets-with-gitguardian/) and give this tutorial an attempt using:

- GitHub
- CircleCI
- GitGuardian

### Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.

### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.

```js
function printMe() {
  console.log("I am a reference example");
}
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
