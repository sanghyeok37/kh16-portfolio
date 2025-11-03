%% Use Case Diagram
usecaseDiagram

actor Guest as G
actor User as U
actor Admin as A

G --> (Search Music)
G --> (Play Preview)

U --> (Search Music)
U --> (Play Full Music)
U --> (Upload Music)
U --> (Like Music)
U --> (Comment Music)
U --> (Manage My Uploads)

A --> (View Pending Music)
A --> (Approve Music)
A --> (Reject Music)
A --> (Approve Edit Request)
A --> (Approve Delete Request)
A --> (Delete Music)
A --> (View History Log)
