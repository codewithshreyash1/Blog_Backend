{
	"info": {
		"_postman_id": "c1759b2d-26d2-478e-8a68-ebbbcc79efbf",
		"name": "Blog_backend",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "39588891"
	},
	"item": [
		{
			"name": "New Request",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://blog-backend-yc6s.onrender.com/api/user",
					"protocol": "https",
					"host": [
						"blog-backend-yc6s",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "https://blog-backend-yc6s.onrender.com/api/user",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\":\"shreyash\",\r\n    \"email\":\"shreyashgaikwad3848@gmail.com\",\r\n    \"password\":\"Abdrcb1718\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog-backend-yc6s.onrender.com/api/user",
					"protocol": "https",
					"host": [
						"blog-backend-yc6s",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "https://blog-backend-yc6s.onrender.com/api/user",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog-backend-yc6s.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blog-backend-yc6s",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		},
		{
			"name": "https://blog-backend-yc6s.onrender.com/api/user",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"title\":\"abhishekBlog\",\r\n    \"content\":\"falatuVDO\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blog-backend-yc6s.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blog-backend-yc6s",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		}
	]
}
