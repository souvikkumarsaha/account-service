# account-service

Account service models and provides operations around the account subdomain in the group pension plan domain.
This services provides the following actions:
1. Create a new account for participant
2. Update the account when the participant enrolls in a plan.
3. Allow the participant to make contributions.
  1. The contribution is divided across the different plans by the contribution instructions that are set. (see account-instructions-service)
4. View the current balance of the account.

## Entity model

![ER Diagram](account-er-model.png)

