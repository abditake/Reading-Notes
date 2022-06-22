# [Class 08: Access Control (ACL)](/README.md)

## [5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

## [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

## [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

<hr>

## 5 steps to RBAC

- ### What is Role Based Access Control (RBAC) and why do we care?
    - A system that gives access to user based on roles within an organization. authorization is given based purely on role of user restricting access to any other roles that the user is not assigned to. This minimizes the risk of having system-wide issues instead of it being a role based issue that is manageable. 

- ### Describe a Role/Permission heirarchy that you might implement using RBAC.
     - The example I would use is a restaurant.

      - Owner
      - payroll(finance dept)
      - Cooks
      - waiters
      - BusBoys
  In this example the owner has access to all information to each role. The accountant or payroll has access only to the information of the employees 

- ### What approach might you take to implement RBAC?

wiki - RBAC

- ### If Authentication is “you are who you say you are,” what is Authorization?
    - Authorization is the access you have as the user.

- ### Name three primary rules defined for RBAC.
    - role assignment
    - role authorization
    - permission authorization
- ### Describe RBAC to a non-technical friend.
    - RBAC is a policy/practice that allows an organization to properly manage the responsibilities and tasks among employees maintain good system security.  

Videos
RBAC tutorial

- ### What Are access rights Associated with? The User? or The Role? Explain.
    - they are associated with the role and not the user. Access rights are defined for roles. 

- ### Access Rights, or Authorization, is activated after a user successfully does what?
    - A user assumes a role. once that role is assumed then they will be given access to rights associated with the role. 
- ### Explain how RBAC might benefit a business.
    - policy can remain unchanged because the policy is associated with roles not the user.
    - employee should be able to activate desired role
    - revisiting least privilege. 
        - you don't negatively impact resources that someone didn't have any reason having access to. 
        -  user in one role has access to a subset of the files
        -  switch roles to gain access to other resources.
        -  selinux