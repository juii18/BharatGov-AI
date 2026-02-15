# GovGuide – System Design Document

## Architecture Overview

User → Streamlit Frontend → Python Backend → Recommendation Engine → Scheme Database → Results

## Components

### Frontend
- Built using Streamlit
- Provides user input interface
- Displays recommended schemes

### Backend
- Developed using Python
- Processes user input
- Matches input with scheme eligibility

### Recommendation Engine
- Uses Natural Language Processing techniques
- Matches user eligibility with scheme dataset

### Database
- Government scheme dataset stored in CSV format
- Contains scheme name, eligibility, and benefits

## Workflow

1. User enters occupation or eligibility details
2. Frontend sends input to backend
3. Backend processes input using recommendation engine
4. System searches scheme database
5. Matching schemes are returned
6. Results displayed to user

## Scalability

System can be deployed on AWS EC2 and use S3 for data storage.

## Future Enhancements

- AI chatbot integration
- Voice input support
- Real-time scheme API integration
- Mobile application
