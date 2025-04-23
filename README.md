AigoTools is an open - source AI web - site navigation system for quick creation and management of navigation sites.

### Core Features
1. **Site Management**: Simple interface for easy site addition, editing, and deletion.
2. **Auto - Collection**: Uses Playwright, Jina, and OpenAI to auto - generate screenshots, crawl, and summarize site info.
3. **User Management**: Clerk - based system for secure user authentication and access control.
4. **Internationalization**: Supports Chinese and English interface switching.
5. **Theme Switching**: Allows users to choose dark or light theme.
6. **SEO Optimization**: Auto - extracts SEO info and generates sitemaps.
7. **Image Storage**: Supports MinIO, AWS S3, and Tencent Cloud COS.

### Deployment
It has two parts: `packages/aigotools` and `packages/crawler`. Can be deployed via Zeabur or locally with `docker - compose`. Prerequisites include Clerk app creation, getting API keys, and deploying databases.

In short, AigoTools is a powerful and user - friendly tool for building navigation platforms.
