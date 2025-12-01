# Contributing to KlikKart

Thank you for considering contributing to KlikKart! We welcome contributions from the community.

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with the following information:
- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Your environment (OS, browser, Node.js version, Java version)

### Suggesting Enhancements

We welcome suggestions for new features or improvements. Please create an issue with:
- A clear and descriptive title
- Detailed description of the proposed enhancement
- Rationale for why this enhancement would be useful
- Any relevant examples or mockups

### Pull Request Process

1. **Fork the repository** and create your branch from `main`
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Follow the existing code style
   - Write clear, descriptive commit messages
   - Add tests if applicable
   - Update documentation as needed

3. **Test your changes**
   - Run backend tests: `cd ecom-proj && ./mvnw test`
   - Test frontend locally: `cd ecom-frontend && npm run dev`
   - Ensure both backend and frontend work together

4. **Commit your changes**
   ```bash
   git commit -m 'Add some feature'
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request**
   - Provide a clear description of the changes
   - Reference any related issues
   - Wait for review and address any feedback

## Development Setup

### Backend (Spring Boot)
```bash
cd ecom-proj
./mvnw clean install
./mvnw spring-boot:run
```

### Frontend (React)
```bash
cd ecom-frontend
npm install
npm run dev
```

## Code Style Guidelines

### Java (Backend)
- Follow standard Java naming conventions
- Use meaningful variable and method names
- Add comments for complex logic
- Keep methods focused and concise

### JavaScript/React (Frontend)
- Use functional components with hooks
- Follow React best practices
- Use meaningful component and variable names
- Keep components focused and reusable

## Commit Message Guidelines

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Examples:
```
feat: add product search functionality
fix: resolve image upload issue
docs: update README with API examples
refactor: simplify product service logic
```

## Code Review Process

All submissions require review. We use GitHub pull requests for this purpose.
- At least one approval is required before merging
- Address all review comments before merging
- Keep pull requests focused on a single feature or fix

## License

By contributing to KlikKart, you agree that your contributions will be licensed under the MIT License.

## Questions?

Feel free to create an issue with your question or reach out to the maintainers.

Thank you for contributing! 🎉
