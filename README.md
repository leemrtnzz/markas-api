
# Markas API

Ini hanya project gabut dari https://markas-api.vercel.app

## API Reference

#### Get info KTP

```http
  GET /api/stalker/ktp
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `nik` | `int` | **Required** terdapat limit, dan reset jam 00.00 |

#### Get info pajak kendaraan (Banten Only)

```http
  GET /api/stalker/pajak
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `nopol`      | `string` | **Required** ex: A1247DE |

#### Get gambar anime

```http
  GET /api/random/anime/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `type`      | `string` | **Required** ["sfw"] |

#### Get 25 Nabi dan biodata

```http
  GET /api/muslim/nabi
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| null      | null | null |


#### Get asmaul husna

```http
  GET /api/muslim/asmaul-husna
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| null      | null | null |

#### Get surat-sholat
Cocok untuk murojaah supaya tidak lupa dengan hafalannya, jadi memberikan rekomendasi surat berdasarkan tingkat modenya. Surat bacaan diambil dari juz 30.

```http
  GET /api/muslim/surat_prayer
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `mode`      | `string` | **Required** ["easy", "medium", "hard", "dificulty", "random"] |


### Get download facebook

```http
  GET /api/dl/fb
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `url`      | `string` | **Required**|

### Get download tiktok

```http
  GET /api/dl/tiktok
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `url`      | `string` | **Required** |

### Get download snack video

```http
  GET /api/dl/snack
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `url`      | `string` | **Required** |
## Feedback

If you have any feedback, please reach out to us at Whatsapp 6283841365567

