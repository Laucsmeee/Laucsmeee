#  Привіт, я Ілля

 Python-розробник, який любить експерименти з API, даними та автоматизацією.  
 Від аналізу погоди до AI — створюю pet-проекти для навчання та розвитку.

---

##  Мої основні проекти

###  Anime Genre Explorer
- Отримує жанри та популярні аніме через **AniList API** (GraphQL).  
- Випадковим чином обирає одне популярне аніме.  

**Технології:** `Python`, `requests`, `GraphQL`

```python
anime = random.choice(anime2["data"]["Page"]["media"])
print(anime['title']['romaji'], anime['genres'])
