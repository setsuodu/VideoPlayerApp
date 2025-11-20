```
Solution/
├── MyApp.Api/                  ← ASP.NET Core 9 Web API 项目
│   ├── Controllers/
│   ├── Application/
│   ├── Domain/
│   ├── Infrastructure/
│   └── appsettings.json
│
├── MyApp.Web/                  ← 独立的 React + TypeScript 项目（Vite 为主流）
│   ├── src/
│   │   ├── api/                ← 自动生成的 axios 实例 + OpenAPI 客户端
│   │   ├── features/           ← 按功能分 slice（类似 .NET 的垂直分片）
│   │   ├── components/
│   │   └── App.tsx
│   ├── public/
│   ├── vite.config.ts
│   └── package.json
│
└── MyApp.sln
```