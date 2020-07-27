# Marketing-Page
**Proposal**

---

- **What problem does your app solve?**
    - **With an easy to use interface for creating a plant watering schedule tailored to each individual plant, WaterMyPlants will remind users when it's time to feed that foliage and quench your plants' thirst.**

- **Be as specific as possible; how does your app solve the problem?**
    - Visual reminder
    - Push notifications
    - How much water
    - When to water
    - Gamification

- **What is the mission statement?**
    - Ensuring that all your plants are consistently watered is actually pretty difficult. Water My Plants is an app that helps to solve those problems.
    - Drunk on responsibility.
    - Don’t kill your plants.

# **Features**

---

- **What features are required for your minimum viable product?**
    - user can sign-up / create an account by providing a unique username, a valid mobile phoneNumber and a password.
    - user can login to an authenticated session using the credentials provided at account creation / signup.
    - Authenticated user can Create, Update and Delete a plant object. At a minimum, each plant must have the following properties:
        - id: Integer
        - nickname: String
        - species : String
        - h2oFrequency: Type determined by implementation
        - image: (optional)
    - Authenticated user can view a list of created plants. A plant can be deleted or selected to present user with a detail view where user can then update any property of the selected plant.
    - Authenticated user can update their phoneNumber and password.
- **What features may you wish to put in a future release?**
    - Authenticated user can set up push notifications to be triggered when an h2oFrequency of any plant arrives / has elapsed.
    - Implement a feature that allows an authenticated user to see an appropriate suggested h2oFrequency based on species using the API of your choice.
    - Authenticated user can upload images of a plant. If no user image is provided, a placeholder image of a plant of the same species populates the view.
    - Gamification
- **What do the top 3 similar apps do for their users?**
    - [https://happyplantapp.com/](https://happyplantapp.com/)
        - Progress (how many days…)
        - Water streaks
        - Time-lapse video – Take pictures of your plants over time and watch them grow!
    - [https://apps.apple.com/us/app/planta-keep-your-plants-alive/id1410126781](https://apps.apple.com/us/app/planta-keep-your-plants-alive/id1410126781)
        - Plant doctor, monitors sunlight.
        - Organize plants by location in the house
        - Scientific names
    - [https://play.google.com/store/apps/details?id=net.kosev.watering&hl=en_US](https://play.google.com/store/apps/details?id=net.kosev.watering&hl=en_US) Waterbot
        - Create flower avatars using phone’s camera
- [https://www.veraplantcareapp.com/](https://www.veraplantcareapp.com/)
- [https://apps.apple.com/us/app/planty/id1356268037](https://apps.apple.com/us/app/planty/id1356268037)
- [https://apps.apple.com/us/app/waterme-gardening-reminders/id1089742494#?platform=iphone](https://apps.apple.com/us/app/waterme-gardening-reminders/id1089742494#?platform=iphone)

**Frameworks - Libraries**

---

- **What 3rd party frameworks are you considering using?**
    - **UI**
        - **HTML**
        - CSS
        - Flexbox
        - Fontawesome
        - Google Fonts
    - **Front End**
        - React
        - Context API
- **Backend**
    - Tomcat
    - Java
    - Postgres
    - Spring boot
    - Jackson
- **Do the API(s) you need require you to contact them to gain access?**
    - Nope
- **Are you required to pay to use said API(s)?**
    - Nope
- **Have you considered using Apple Frameworks?** ***(MapKit, Healthkit, ARKit?)***
    - Never
- 
    - ****

**Target Audience**

---

- **Who is your target audience? Be specific.**
    - Procrastinators
    - Peeps with plants
    - Likes a schedule
    - Forgetful people
    - LAZY
    - New plant owners
    - House sitters
    - 
- **What feedback have you gotten from potential users?**
    - Scientific names
    - 
- **How have you validated this problem and your solution with your target audience?**
    - Nope, just assumed.

# **Prototype Key Feature(s)**

---

- **How long do you think it will take to implement these features?**
    - About 4 days
- **Do you anticipate working on stretch functionality after completion of a Minimal Viable Product?**
    - Always