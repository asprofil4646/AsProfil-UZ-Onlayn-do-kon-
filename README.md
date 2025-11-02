cd /path/to/your/project
cat > .gitignore <<'EOF'
node_modules/
dist/
.env
.env.local
.vscode/
.DS_Store
EOF
git init
git add .
git commit -m "Initial commit"
git
