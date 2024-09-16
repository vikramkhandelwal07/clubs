# University admin Dashboard



```mermaid
graph LR
    A[University Admin Dashboard] --> B[Overview: Stats & Insights]
    A --> C[Pending Approvals]
    A --> D[Club Management]
    A --> E[Event Management]
    A --> F[System Settings]
    A --> G[Notifications]
    B --> H[Clubs Overview: List of Clubs]
    B --> I[Event Overview: Participation Stats]
    D --> J[Manage Individual Clubs]
    E --> K[Approve Events]
    F --> L[Manage Platform Policies]

```




# Club admin Dashboard
### **Wireframe 2: Club Admin Dashboard**


#### Sections:

- **Club Overview**
- **Manage Members**
- **Event Creation/Edit**
- **Club Analytics**
- **Profile Settings**
- **Notifications**

### **Wireframe Layout Overview:**

1. **Club Overview**: At the top of the dashboard, there will be a small section for club information, including the club's name, description, logo, and contact details.
    
2. **Manage Members**: This section will include options for adding, removing, or inviting members. Admins can assign different roles to members (e.g., Event Manager, Club President) and manage permissions.
    
3. **Create/Edit Events**: Club admins can view existing events, create new ones, and edit past ones. This includes form fields like event name, date, time, location, and description. There will also be options for attaching flyers and other materials.
    
4. **Analytics**: This section gives club admins insights into club activity, event participation, and member engagement. Graphs and charts will make this data easy to digest.
    
5. **Profile Settings**: This area allows club admins to edit club profiles, update contact information, and manage the club's social links.
    
6. **Notifications**: Admins can receive reminders for upcoming events and notifications about pending member invitations.
```mermaid
graph LR
    A[Club Admin Dashboard] --> B[Club Overview]
    A --> C[Manage Members]
    A --> D[Create/Edit Events]
    A --> E[View Analytics]
    A --> F[Profile Settings]
    A --> G[Notifications]
    
    B --> B1[Club Name]
    B --> B2[Club Description]
    B --> B3[Club Logo and Contact Info]
    
    C --> C1[Add/Remove Members]
    C --> C2[Invite Members via Email]
    C --> C3[Assign Roles]
    
    D --> D1[Event List]
    D --> D2[Create New Event Form]
    D --> D3[Edit Existing Event]
    
    E --> E1[Event Participation Stats]
    E --> E2[Member Activity Data]
    E --> E3[Engagement Metrics]
    
    F --> F1[Club Profile: Editable Details]
    F --> F2[Social Links]
    F --> F3[Club Preferences]
    
    G --> G1[Upcoming Event Reminders]
    G --> G2[Pending Invitations]

```


# Student Dashboard
### **Wireframe 3: Student Dashboard**

#### Sections:

- **Club Discovery**
- **Event Listings**
- **My Clubs**
- **Notifications**
- **Profile Management**

```mermaid
graph LR
    A[Student Dashboard] --> B[Club Discovery]
    A --> C[Event Listings]
    A --> D[My Clubs]
    A --> E[Notifications]
    A --> F[Profile Management]
    
    B --> B1[Search by Category]
    B --> B2[Popular Clubs]
    B --> B3[Recommended Clubs]
    
    C --> C1[Upcoming Events]
    C --> C2[Event Filters - like date category etc]
    C --> C3[Event Registration]
    
    D --> D1[Joined Clubs List]
    D --> D2[Leave Club Option]
    
    E --> E1[Event Reminders]
    E --> E2[New Club Updates]
    
    F --> F1[Edit Profile Information]
    F --> F2[Change Password]
    F --> F3[Profile Picture Upload]
```
### **Wireframe Layout Overview:**

1. **Club Discovery**:
    
    - A search bar allows students to search for clubs by name or category.
    - Popular and recommended clubs based on student interests and engagement will be displayed in card form, with a "Join Club" button for each.
2. **Event Listings**:
    
    - Shows upcoming events from all clubs.
    - Filters allow students to narrow down events by date, category, or club.
    - A "Register" button next to each event shows status (e.g., registered or not).
3. **My Clubs**:
    
    - Displays a list of clubs the student has joined, with the option to leave a club.
    - Clicking on a club takes them to the club’s profile page.
4. **Notifications**:
    
    - Notifications for upcoming events, new posts from clubs, and invites to events.
    - Allows students to manage notifications (e.g., turn off updates for specific clubs).
5. **Profile Management**:
    
    - Basic profile settings where students can update their information (name, bio, etc.).
    - Option to change the password and upload a profile picture.



# Club 
### **Wireframe 4: Club Directory/Club Page**

#### Sections:

- **Club Search**
- **Club Profile**
- **Join/Leave Club**
- **Past Events**
- **Club Admin Contact**

```mermaid
flowchart LR
    A[Club Directory] --> B[Search for Clubs]
    A --> C[Club Categories]
    A --> D[Club Profile Page]
    
    D --> D1[Club Name & Description]
    D --> D2[Club Admin Contact]
    D --> D3[Join/Leave Club Button]
    D --> D4[Past Events]
    D --> D5[Upcoming Events]
    D --> D6[Member List - if public]
    
    B --> B1[Search Bar]
    B --> B2[Filters -Category, Popularity]
    
    C --> C1[Category List -e.g., Sports, Music, Tech]
    C --> C2[Browse Clubs by Category]

```
### **Wireframe Layout Overview:**

1. **Club Search**:
    
    - A search bar where students can enter club names or keywords.
    - Filters allow them to sort clubs by categories like sports, music, tech, and more.
2. **Club Profile**:
    
    - Contains the club’s name, description, and key details like meeting times, the number of members, and a contact form for reaching the club admin.
    - "Join/Leave Club" button based on the student's current membership status.
3. **Past Events**:
    
    - A section dedicated to displaying previous events, which gives new students a sense of the club's activities and engagements.
4. **Upcoming Events**:
    
    - Similar to past events, but focused on future dates with registration buttons.
5. **Club Admin Contact**:
    
    - Direct contact information for club admins for students interested in learning more.


# Event
### **Wireframe 5: Event Page**

#### Sections:

- **Event Details**
- **Event Registration**
- **Event Attendees (if public)**
- **Related Events**

```mermaid
graph LR
    A[Event Page] --> B[Event Details]
    A --> C[Event Registration]
    A --> D[Event Attendees]
    A --> E[Related Events]
    
    B --> B1[Event Name]
    B --> B2[Event Date, Time, Location]
    B --> B3[Event Description]
    B --> B4[Event Flyers/Images]
    
    C --> C1[Register Button]
    C --> C2[Registration Status]
    
    D --> D1[List of Public Attendees]
    D --> D2[Profile Link of Attendees]
    
    E --> E1[Related Events List]
    E --> E2[Suggested Events]

```


### **Wireframe Layout Overview:**

1. **Event Details**:
    
    - The top of the page includes the event name, date, time, location, and description.
    - If the event has media (e.g., images or flyers), they will be displayed here.
2. **Event Registration**:
    
    - A button to register/unregister for the event, with a clear status indicator (e.g., "You are registered" or "Registration Closed").
3. **Event Attendees**:
    
    - If the event allows public attendee lists, students can view who is attending and click on profiles for further connection.
4. **Related Events**:
    
    - A list of similar or related events based on the student's interests or the clubs they have joined.


# Profile Page
### **Wireframe 6: Profile Page (for all user types)**

#### Sections:

- **Profile Picture**
- **User Information**
- **Joined Clubs**
- **Attended Events**
- **Profile Settings**


```mermaid
graph LR
    A[Profile Page] --> B[Profile Picture]
    A --> C[User Information]
    A --> D[Joined Clubs]
    A --> E[Attended Events]
    A --> F[Profile Settings]
    
    B --> B1[Upload New Picture Button]
    
    C --> C1[Edit Name]
    C --> C2[Edit Email]
    C --> C3[Bio Section]
    
    D --> D1[List of Joined Clubs]
    D --> D2[Club Links]
    
    E --> E1[Attended Events List]
    E --> E2[Upcoming Events]
    
    F --> F1[Password Change Option]
    F --> F2[Update Notifications Settings]

```
### **Wireframe Layout Overview:**

1. **Profile Picture**:
    
    - At the top, students can upload a profile picture. Club admins will also have similar functionality.
2. **User Information**:
    
    - Editable fields for name, email, and a short bio.
3. **Joined Clubs**:
    
    - A list of all clubs the user has joined, with quick links to the clubs’ pages.
4. **Attended Events**:
    
    - Displays a history of events attended, with filters for past and upcoming events.
5. **Profile Settings**:
    
    - Includes options to change the password, manage email notifications, and other profile settings.
