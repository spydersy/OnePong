# OnePong

This project is about creating a website for the mighty Pong contest!

### Languages and Technologies
- Backend (Rest Api): [NestJS](https://nestjs.com/) / [TypeScript](https://www.typescriptlang.org/)
- Frontend: [ReactJS](https://reactjs.org/) / [TypeScript](https://www.typescriptlang.org/)
- Database: [PostgreSQL](https://www.postgresql.org/)
- ORM (Object–relational mapping): [Prisma](https://www.prisma.io/)
- Deployment: [Docker](https://www.docker.com/) / [Docker-compose](https://docs.docker.com/compose/)
- Utilities: [Swagger UI](https://swagger.io/)

## User Account
- The user can login using the OAuth system of 42 intranet.

- The user should be able to choose a unique name that will be displayed on the website.
- The user can upload an avatar. If the user doesn’t upload an avatar, a default one is set.
- The user can enable two-factor authentication.
- The user can add other users as friends and see their current status (online, offline, in a game).
- Stats (such as: wins and losses, ladder level, achievements, and so forth) are displayed on the user profile.
- Each user have a Match History including 1v1 games, ladder, and anything else useful. Anyone who is logged in can to consult it.

### [Demo] Authentication using 42Intranet / 2FA:
![auth GIF](https://github.com/spydersy/OnePong/blob/main/gif/auth_2fa.gif)

### [Demo] Real-Time Status(online/offline/in game):
![auth GIF](https://github.com/spydersy/OnePong/blob/main/gif/realtime_status.gif)

## Chat
- The user can create channels (chat rooms) that can be either public, or private, or protected by a password.
- The user can send direct messages to other users.
- The user can block other users. This way, they will see no more messages from the account they blocked.
- The user who has created a new channel is automatically set as the channel owner until they leave it.
- The channel owner can set a password required to access the channel, change it, and also remove it.
- The channel owner is a channel administrator. They can set other users as administrators.
- The administrators of a channel can ban or mute users for a limited time.
- The user can invite other users to play a Pong game through the chat interface.
- The user should be able to access other players profiles through the chat interface.

### [Demo] Chat:
![chat GIF](https://github.com/spydersy/OnePong/blob/main/gif/chat.gif)

![group chat GIF](https://github.com/spydersy/OnePong/blob/main/gif/group.gif)

## Pong Game
- Users should be able to play a live Pong game versus another player directly on the website.
- Matchmaking system: the user can join a queue until they get automatically matched with someone else.
- responsive game.
- The user can watch a live play between other users without interfering with it.

### [Demo] Game / Matchmaking system:
![chat GIF](https://github.com/spydersy/OnePong/blob/main/gif/game.gif)

### [Demo] AI mode / Spectating mode:
![group chat GIF](https://github.com/spydersy/OnePong/blob/main/gif/ai_mode_stream.gif)