# ST10395938\_PROG6212\_POEPart1



## Project Overview



The *Contract Monthly Claim System (CMCS)* allows IC lecturers to submit monthly claims based on hours worked and hourly rates. Each claim undergoes approval by both the *Programme Coordinator* and the *Academic Manager*, emphasizing accuracy and accountability.



Key functionalities include:



- Submission of monthly claims with calculated totals.

- Uploading and downloading supporting documents.

- Commenting and approval workflow for both coordinators and managers.

- Interactive and responsive user interface using C# and ASP.NET Core MVC.



## Folder Structure



YourProject

│

├── Controllers

│ └── HomeController.cs

│

├── Views

│ ├── Home

│ │ ├── Index.cshtml

│ │ ├── SubmitClaim.cshtml

│ │ ├── TrackClaim.cshtml

│ │ ├── CoordinatorApproval.cshtml

│ │ └── ManagerApproval.cshtml

│ │

│ └── Shared

│ └── \_Layout.cshtml

│

└── Program.cs / Startup.cs (default ASP.NET Core entry points)



## Features



- **Lecturer Claim Submission**: Enter month, year, hours worked, rate, total, and upload supporting documents.

- **Track Claims**: View submitted claims with real-time filtering/search by Claim ID.

- **Coordinator Approval**: Approve or reject claims, add comments, and download documents.

- **Manager Approval**: Final approval workflow with comments and document access.



## Technologies Used



- **ASP.NET Core MVC** (.NET 9.0)

- **C#** for backend logic

- **Razor Views** for UI templates

- **Bootstrap 5** for styling and responsive layout



Author



**Student Number:** ST10395938



**Module** PROG6212 - Programming 2B



