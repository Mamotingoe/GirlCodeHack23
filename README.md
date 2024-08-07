# GirlCodeHack23
WhatsApp chatbot that helps women in tech find jobs with the best HR policies and frameworks and help them learn about their labour law options and also help recruiters learn about policy changes they can make in order to rank hire on job searches.

sequenceDiagram
    participant User
    participant AllyBot
    participant JobDatabase

    User->>AllyBot: Start conversation
    AllyBot->>User: Welcome message and profile creation prompt
    User->>AllyBot: Provide profile information
    AllyBot->>User: Ask for job preferences
    User->>AllyBot: Share job preferences
    AllyBot->>User: Request policy priorities
    User->>AllyBot: Specify policy priorities
    AllyBot->>JobDatabase: Query jobs based on preferences and policies
    JobDatabase->>AllyBot: Return matching job listings
    AllyBot->>User: Present job recommendations
    User->>AllyBot: Request more details or next steps
    AllyBot->>User: Provide additional information or guidance
