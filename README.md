# Laravel Vapor Test

Skeleton application that can be deployed using [https://vapor.laravel.com](Laravel Vapor) to test out how it works. Check the "AWS Services Used/Tested` to see which AWS services are used by the application.

## App

The application contains Laravel's basic generated authentication system that requires users to validate their email address by sending a queueable email. Once an account is verified a user can sign-in to the application.

## AWS Services Used/Tested

- Lambda (Serverless Functions)
- RDS (Database)
- SES (Email) - Must add e-mail address to SES that is defined in the `.env` (`MAIL_FROM_ADDRESS` key)
- SQS (Queue)
- DynamoDB (Caching)
