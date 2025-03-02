# CodeFit

## Project Overview

CodeFit is a *candidate recruiting web application* that validates a candidate's *GitHub profile* to assist companies in hiring decisions. Companies can create accounts, add candidates by providing their GitHub URLs, set benchmarks, compare candidates, and analyze their commit and pull request histories through interactive graphs.

## Key Features & Technologies

### Key Features:

- **Company Registration**: Companies can create and manage their accounts.
- **Candidate Management**: Add candidates via their *GitHub profiles*.
- **Benchmarking**: Set hiring benchmarks based on GitHub activities.
- **Candidate Comparison**: Compare multiple candidates based on coding activity.
- **Graphical Insights**: View commit and pull request (*PR*) history in an interactive format.

### Technologies Used:

- **Frontend**: *Next.js*
- **Backend**: *Node.js with Express.js*
- **Database**: *MongoDB*
- **GitHub API**: Fetch candidate data
- **Graph Libraries**: *(e.g., Chart.js / D3.js)* for visualizing commit and PR history
- **Authentication**: *JWT-based authentication* for companies

## Setup Instructions

### Prerequisites:

Ensure you have the following installed on your system:

- *Node.js & npm*
- *MongoDB* (or use MongoDB Atlas)

### Steps to Run:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/candidate-recruiting-app.git
   cd candidate-recruiting-app
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Set up environment variables**:
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   GITHUB_API_KEY=your_github_api_key
   JWT_SECRET=your_secret_key
   ```
4. **Run the application**:
   ```bash
   npm run dev
   ```
5. **Access the application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment

A live version of the application is available at:
🔗 **[Deployed Application](https://your-deployment-url.com)**

## Additional Resources

For large datasets, logs, or notebooks used in the project, refer to our shared drive:
📂 **[Google Drive Link](https://drive.google.com/your-shared-link)**

## Contact

For any queries or issues, feel free to open an issue in the repository or contact us at *your-email@example.com*.

