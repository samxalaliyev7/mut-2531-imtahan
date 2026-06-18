# GitHub Pages deploy təlimatı

## Web interfeys ilə

1. GitHub hesabına daxil olun.
2. `New repository` seçin.
3. Repository adını yazın: `mut-2531-imtahan`.
4. Public seçin.
5. `Create repository` klikləyin.
6. Bu qovluqdakı faylları GitHub-a upload edin: `index.html`, `questions-data.js`, `assets/`, `README.md`, `.nojekyll` və s.
7. `Settings > Pages` bölməsinə daxil olun.
8. Source olaraq `Deploy from a branch` seçin.
9. Branch `main`, folder `/root` seçin.
10. `Save` edin.

Bir neçə dəqiqədən sonra sayt bu formada açılacaq:

```text
https://SENIN_GITHUB_USERNAME.github.io/mut-2531-imtahan/
```

## Git komandaları ilə

```bash
git init
git add .
git commit -m "MUT-2531 exam system"
git branch -M main
git remote add origin https://github.com/SENIN_GITHUB_USERNAME/mut-2531-imtahan.git
git push -u origin main
```

Sonra `Settings > Pages` hissəsindən GitHub Pages-i aktiv edin.
