# video-streaming
Just a sample repo for streaming videos

The project includes below services
1. Account Service
2. Video Browse Service
3. Video Streaming Service
4. Video Upload Service

## User Service
This holds account specific information and it just saves / restrieves user information such as username, email, password

Different type of users and their roles.
1. Admin
2. End User
3. Video creator

## Video Browse Service
It shows the list of video thumbnails by category, genre. It allows the user to filter videos based on title, genre, category etc.

## Video Streaming Service
It just takes care of the video streaming service.

## Video Upload Service
A service which helps creators to help upload videos.

Brain storming about the video streaming service.
1. What is a Video ?
  It contains information about the video such as
```JSON
{
  "title"       : "First Video",
  "description" : "Hey Guys, I am at the zoo, In this video we are going to show..",
  "genre"       : "ShortVideo",
  "type"        : "Recorded",
  "duration"    : "5:28",
  "format"      : "ovi",
  "creator"     : "123..",
  "createdDate" : 1687885303419
}
```
2. What is a User ?
   A user which contains information specific to users
   ```JSON
   {
     "firstName"   : "John",
     "lastName"    : "Doe",
     "userKey"     : "123..",
     "dateOfBirth" : 1687885303419,
     "email"       : "johndoe@example.com",
     "password"    : "****",
     "phone"       : "+91234..",
     "country"     : "IN",
     "roles"       : [ "ROLE_ADMIN", "ROLE_CONSUMER", "ROLE_CONTENT_CREATOR" ]
   }
   ```
3. What is an Account ?
   An account which holds account specific information
```JSON
  {
    "accountKey"  : "123..",
    "createdDate" : 1687885303419,
    "name"        : "Uber",
    "email"       : "johndoe@example.com",
    "country"     : "IN"
    "users"       : [ "1234", "5678" ]
  }
  ```
users hold userkeys



