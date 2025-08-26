# Portfolio Website File Structure

## 📁 S3 Bucket Structure (Static Website)

```
portfolio-website-bucket/
│
├── index.html                 # Main portfolio file (the HTML from artifact)
├── assets/
│   ├── styles/
│   │   └── styles.css         # Extract CSS if needed
│   ├── js/
│   │   └── script.js         # Optional: Extract JavaScript if needed
│   ├── images/
│   │   ├── profile.jpg       # Your profile photo
│   │   ├── project1.jpg      # Project screenshots
│   │   ├── project2.jpg
│   │   
│   └── docs/
│      └── resume.pdf        # Your resume/CV
└── error.html                # Custom 404 error page

```

## 🔧 Lambda Functions Structure

```
lambda-functions/
│
├── contact-form/
│   ├── index.js             # Contact form Lambda function
│   ├── package.json         # Dependencies
│   └── README.md           # Setup instructions
│
└── visitor-counter/
    ├── index.js             # Visitor counter Lambda function
    ├── package.json         # Dependencies
    └── README.md           # Setup instructions

```
## 📋 Checklist

- [ ] Uploaded website files to GitHub
- [ ] Deployed website using Amplify + GitHub integration
- [ ] Tested automatic deployment by making a code change
- [ ] Create DynamoDB table "VisitorCounter"
- [ ] Deploy visitor counter Lambda function
- [ ] Deploy contact form Lambda function
- [ ] Configure SES for email sending
- [ ] Update Lambda function URLs in index.html
- [ ] Test contact form functionality
- [ ] Test visitor counter
- [ ] Configure custom domain (optional)



This structure provides a complete, production-ready setup for your portfolio website with serverless backend functionality!