# Pipeline Process

## The pipeline will have 2 process are Build and Deploy

#### Build process will run these steps below in order:
1. Spin up environment
2. Prepare environment variables
3. Install Node.js 14.15
4. Checkout code
5. Install AWS CLI - latest
6. Configure AWS Access Key ID
7. Install Front-End Dependencies
7. Install API Dependencies
9. Front-End Lint
10. Front-End Build
11. API Build

#### Deploy process will run these steps below in order:
1. Spin up environment
2. Preparing environment variables
3. Install Node.js 14.15
4. Setting Up Elastic Beanstalk CLI
5. Install AWS CLI - latest
6. Configure AWS Access Key ID
7. Checkout code
8. Deploy App