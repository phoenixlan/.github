# Phoenix LAN

Phoenix LAN is a LAN party for youth located in Asker, Norway. One of our main goals is to provide youth with an arena where they can discover their interest for technology, and nurture it in ways not possible alone in their bedroom. We offer them large scale networking and professional-grade software development with systems designed to be big and safe yet simple to work with.

# Goal

We want to make more youth realize their love for technical systems by natural exposure to tinkering with it. Having done LAN parties for over 10 years, we have noticed a clear trend where more kids gain only surface-level technological skills due to modern technology working _too well_. There is no need to get your hands dirty any more. We hope the work we put in here can offset this effect in our local community, and open the door to great careers and lives for more youth.

# What is available here?

Our main project is the Phoenix Event Management System, an **Open-Source system for running volunteer events**. People working together out of their own interest to make great events is awesome, and we want to help make this experience easier by providing the necessary software to do this for free. No more google forms spreadsheet crew applications. No more for-profit systems.

 [PhoenixAPI](https://github.com/phoenixlan/phoenixapi-v1) - a Python-based API server for managing volunteer events. It supports ticket sales, seatmaps, info screens, competition registration, crew applications, HR management, and many other useful features. While the API server itself is a monolith, the Phoenix EMS is designed to be modular. Using [PhoenixJS](https://github.com/phoenixlan/phoenixjs) you can write your own frontend to the API server and interface with it using a simple javascript API. If you want to use the Phoenix EMS for your event, you can use the API server + admin panel(the crew page) and write your own frontend for your users. If you don't have those resources, you can also use everything as-is, although you may want a programmer to disable features you don't need.

The service requires hosting. If you have a developer in your team, they can probably fix something for you. If not, we hope to document how to easily host it for non-technical users in the future. Please note that hosting any _any kind_ of server requires a certain level of knowledge, as you are responsible for your users' data.
