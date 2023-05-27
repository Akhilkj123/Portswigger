## Access Control Vulnerabilities
### Access Control
 Access control (or authorization) is the application of constraints on who (or what) can perform attempted actions or access resources that they have requested. In the context of web applications, access control is dependent on authentication and session management:

- **Authentication** identifies the user and confirms that they are who they say they are.
- **Session management** identifies which subsequent HTTP requests are being made by that same user.
- **Access control** determines whether the user is allowed to carry out the action that they are attempting to perform.

#### Vertical Access Control
Vertical access controls are mechanisms that restrict access to sensitive functionality that is not available to other types of users. 

#### Horizontal access controls
Horizontal access controls are mechanisms that restrict access to resources to the users who are specifically allowed to access those resources. 

#### Context-dependent access controls
Context-dependent access controls restrict access to functionality and resources based upon the state of the application or the user's interaction with it. 

### Broken Access Control
Broken access controls are a commonly encountered and often critical security vulnerability.

#### Vertical privilege escalation
If a user can gain access to functionality that they are not permitted to access then this is vertical privilege escalation. 

#### Horizontal privilege escalation
Horizontal privilege escalation arises when a user is able to gain access to resources belonging to another user, instead of their own resources of that type.

