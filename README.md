git clone https://github.com/talha-nagorik/breast-cancer-ai.git
cd breast-cancer-ai




# শুধুমাত্র একবার চালান: uv ইনস্টল করার জন্য
pip install uv

# এখন uv sync চালান
uv sync



cd tailwindcss
pnpm install
cd ..



uv run python manage_db.py init


uv run fastapi dev app/main.py

cd tailwindcss
pnpm run dev
