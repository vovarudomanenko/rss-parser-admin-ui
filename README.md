# rss-parser-admin-ui

![alt text](preview.png)

### Getting started
1. Create in ```src``` folder ```.env``` file based on ```.env.example```
2. run ```make up``` command
3. open ```https://localhost:8000/admin/posts```
4. sign in, login and password are already pre-populated

| Task                                             | Status  |
|--------------------------------------------------|---------|
| jwt auth                                         | ✅       |
| crud                                             | ✅       |
| schedule rss feed parsing                        | ✅       |
| ReactJS admin UI(sort, filter, paginate, search) | ✅       |
| REST API                                         | ✅       |
| dockerize                                        | ✅       |

Commands:  
    ```php artisan lifehacker:rss-feed``` - manually parse rss feed

