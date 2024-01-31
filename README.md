# course

This is the course repo for Saint Louis Univeristy Computer Science 5030, "Principles of Software Development". When working on activities for the entire class, students should submit work here. When working on team projects, each team should use the team project repo. This repo is intended to help the class work together towards our common goals. Students will primarily use this repo as a way to reflect on progress and share resources. This repo is primarily a navigational tool. Students should ask themselves regularly, "Am I on `course`?". If you are on course, you are headed in the right direction.

The `crew_manual` directory contains content for a statically generated website using the Astro Framework. Students will be required to keep the `crew_manual` updated with various maintenance records regarding their progress. This work is part of "keeping the old systems working" that everyone in the crew must collaborate on. This work maintaining the existing system must be done at the same time that everyone needs to build the new systems intended for future success. Existing systems are fairly stable, and crew members generally just need to keep regular logs of key activities, critical maintenance, and any significant changes.

New systems that students build are designated by our standards and regulations as `experimental` until their value is demonstrated, their engineering is validated, and safety is confirmed. As such, all new systems built in separate code repositories by small, dedicated teams. That said, the value that these experimental systems are intended to produce is vital for the long term success of our enterprise. Because of this, work on `experimental` systens not completed by the crew in the alloted time as well as work that does not meet our strict quality standards will result in demotion or more serious consequences, up to and including removal from the crew.

Remember colleagues, "maintain course."

# Just a Second Connector

#Author
Your Name

## Personal Reflections
Add any personal reflections, considerations, or key decisions made during the development process.

## Production Deployment Assumptions

1. Platform:
   - Assumption: The production deployment will be hosted on AWS.
   - Rationale: AWS provides scalable infrastructure suitable for our application.

2. Database:
   - Assumption: PostgreSQL will be used as the production database hosted on Amazon RDS.
   - Rationale: PostgreSQL offers a reliable and scalable solution for our data storage needs.

3. Proxy:
   - Assumption: Nginx will be used as a reverse proxy in production.
   - Rationale: Nginx provides features like SSL termination and load balancing.

4. Environment Variables:
   - Assumption: Production deployment requires specific environment variables such as `PROD_DATABASE_URL`.
   - Rationale: Configuring environment variables ensures security and flexibility in deployment.

## Getting Started

Add instructions for running the application in both development and production environments.

...
