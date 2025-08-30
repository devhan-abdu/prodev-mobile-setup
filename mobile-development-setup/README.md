# 1) Clone and enter
git clone <your-repo-url>
cd <your-repo-dir>

# 2) Install deps
pnpm install

# 3) Copy env template
cp .env.example .env.local   # for Next.js dev
cp .env.example .env         # for server-only apps

# 4) Start dev
pnpm dev
