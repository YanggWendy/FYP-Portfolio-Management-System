# FYP-Portfolio-Management-System

## Description
Application for the MaxCloud ecosystem. Built with custom stack to provide robust backend services and data management capabilities.

## Tech Stack
- **Language:** Unknown
- **Framework:** Custom
- **Build Tool:** Other
- **Key Libraries:** Depends on configuration (see package.json/pom.xml/build.gradle)

## Project Structure
- `src/` - Source code
- `test/` - Test files
- Configuration files at root (pom.xml, package.json, build.gradle, etc.)

## Key Features & Capabilities
- REST API endpoints
- Data persistence layer
- Authentication & Authorization
- Error handling & validation
- Database integration

## Common Workflows

### Setup
```bash
# Clone and install dependencies
git clone <repo-url>
cd FYP-Portfolio-Management-System

# For Java/Kotlin projects
./gradlew build

# For Node.js projects
npm install
```

### Build
```bash
# Kotlin/Spring Boot
./gradlew build

# Node.js
npm run build
```

### Test
```bash
# Kotlin/Spring Boot
./gradlew test

# Node.js
npm test
```

### Deploy
Documentation in deployment configuration files or CI/CD pipeline.

## AI Agent Management
- **Can AI modify code?** Yes - API endpoints, services, data models
- **Can AI run tests?** Yes - Run test suites with gradle test or npm test
- **Can AI deploy?** Limited - Can build, but deployment requires credentials
- **Key files to know:**
  - `build.gradle.kts` or `pom.xml` (Java/Kotlin)
  - `package.json` (Node.js)
  - `src/main/` (Source code)
  - `src/test/` (Tests)
- **How AI can contribute:**
  - Fix bugs and implement features in API endpoints
  - Write unit tests
  - Refactor code for maintainability
  - Update API documentation
  - Optimize database queries
- **Configuration files:**
  - Environment variables in `.env` or application.yml
  - Database connection strings
  - API credentials
- **Database/External deps:**
  - MySQL, PostgreSQL, or MongoDB (varies by project)
  - Redis for caching (in some services)
  - External APIs for third-party integrations
- **Build/Test commands:**
  - `./gradlew build` (Gradle projects)
  - `mvn clean package` (Maven projects)
  - `npm run build` (Node.js)
  - `npm test` or `./gradlew test`

## Important Notes
- Ensure all dependencies are installed before building
- Check environment variables and configuration files before running
- Database migrations may be required on first setup
- Review .gitignore for sensitive files not to be committed

