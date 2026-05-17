# Corolas Agent Studio

corater.corolas.top | Corolas子项目

## 简介
智能体创作工作室，提供可视化Agent构建、编排与发布平台。

## 技术栈
- Frontend: React 19 + TypeScript + Vite
- Styling: Tailwind CSS + shadcn/ui
- Backend: Supabase (Auth + PostgreSQL + Edge Functions)
- Deploy: Vercel (GitHub Push → Auto Deploy)
- CI/CD: GitHub Actions

## 环境变量
| 变量 | 说明 |
|------|------|
| VITE_SUPABASE_URL | Supabase项目URL |
| VITE_SUPABASE_ANON_KEY | Supabase Anon Key |

## 数据库
Supabase项目: https://supabase.com/dashboard/project/corolas-er

## 本地开发
```bash
git clone https://github.com/CA53411/er.git
cd er
npm install
npm run dev
```

## 部署
Push到main分支自动触发Vercel部署
