# MUT-2531aqa İmtahan Sistemi

Bu qovluq GitHub Pages-ə yükləmək üçün hazırlanmış public statik versiyadır.

## Daxildir

- 4 fənn üzrə test sistemi
- Login/parol girişi
- MUT-2531aqa tələbə siyahısı
- Hər fənn üçün ayrıca Score Board
- 50 sual / 50 dəqiqə imtahan rejimi
- Xətti cəbr sualları PDF-dən şəkil formatında dəqiq əlavə olunub
- Cavab variantları hər cəhddə qarışdırılır

## GitHub Pages-ə yükləmə

1. GitHub-da yeni repository yaradın. Məsələn: `mut-2531-imtahan`.
2. Bu qovluğun içindəki bütün faylları repository-nin kök hissəsinə yükləyin.
3. Repository-də `Settings > Pages` bölməsinə keçin.
4. `Build and deployment` hissəsində `Deploy from a branch` seçin.
5. Branch: `main`, folder: `/root` seçin və `Save` edin.
6. Bir neçə dəqiqədən sonra link belə olacaq:

```text
https://GITHUB_USERNAME.github.io/mut-2531-imtahan/
```

## Vacib təhlükəsizlik qeydi

Bu GitHub Pages versiyası statik MVP-dir. Ona görə:

- Nəticələr hər cihazın öz browser yaddaşında saxlanır.
- Müəllim/admin bütün tələbələrin nəticəsini mərkəzi bazada avtomatik görə bilməz.
- Public GitHub reposunda real imtahan təhlükəsizliyi tam təmin olunmur.
- Giriş CSV faylını public repository-yə yükləməyin.

Mərkəzləşdirilmiş nəticə, real admin panel və təhlükəsiz imtahan üçün backend/database versiyası lazımdır.

## Admin girişi

```text
Login: admin
Parol: admin2531
```

Tələbə login/parolları ayrıca private CSV faylındadır və public GitHub reposuna əlavə edilməməlidir.
