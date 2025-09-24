# AI Room Designer

An AI-powered web application that helps users design rooms based on photos and style preferences. This application uses OpenAI's APIs and Azure AI Search for intelligent product recommendations and room layout suggestions.

## Features

- Photo upload and room dimension capture
- Style preference selection with Norwegian market categories
- AI-powered room analysis and product recommendations
- Interactive room layout visualization
- Mobile-first responsive design

## Technical Stack

- Framework: Svelte
- AI Integration: OpenAI API
- Search: Azure AI Search
- Vector Search for product matching
- SVG-based room visualization

## Project Structure

```
src/
├── +page.svelte           # Main application component
├── components/            # Reusable UI components
├── services/             # API integration services
├── types/               # TypeScript type definitions
└── assets/              # Static assets
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```
   OPENAI_API_KEY=your_key_here
   AZURE_SEARCH_KEY=your_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Development

### Available Scripts

- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run preview`: Preview production build
- `npm run test`: Run tests
- `npm run lint`: Lint code

### Component Development

Follow these guidelines when creating new components:
- Use TypeScript for type safety
- Follow Svelte best practices
- Include component documentation
- Add appropriate tests

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Create a pull request

## License

[License details to be added]