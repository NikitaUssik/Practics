# Добавь любой файл (например, README)
echo "# MyApp" > README.md
git add README.md
git commit -m "Initial commit"
git tag v1.0.0  # создаём тег
git push origin main --tags
