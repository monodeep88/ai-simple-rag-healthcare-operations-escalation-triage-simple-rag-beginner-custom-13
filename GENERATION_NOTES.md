# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: Real Estate Policy Assistant

Template path: templates/simple-rag/real-estate-policy-assistant

Short description:

AI-powered triage system for healthcare operations escalation

Architecture notes:

- Use of containerization and service registry for scalability and maintainability

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: Use of containerization and service registry for scalability and maintainability
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: API Gateway: Handles incoming requests and routes them to the appropriate service; Service Registry: Manages service instances and their metadata; Machine Learning Model: Trained model for predicting patient outcomes
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: Patient Information Form: Collects patient information and sends it to the API Gateway; Triage Result Display: Displays the triage result to the user
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: Unit testing, integration testing, and end-to-end testing
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Patient Information Collection: Collects patient information and sends it to the API Gateway; Triage Prediction: Uses the machine learning model to predict the patient's outcome; Triage Result Display: Displays the triage result to the user
