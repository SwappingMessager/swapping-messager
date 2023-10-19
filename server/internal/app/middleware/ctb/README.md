# ctb - Client To Backend

Your backend must implement the following interfaces:

- user: Example: `getUserById(id string) (User, error)`
- auth: Example: `authUser(id string, token string) (User, error)`
- configuration: Example: `getConfiguration(k string) (Configuration, error)`
- callback: Example: `onMessage(msg Message) (Message, error)`
