# Moe-Counter

多种风格可选的萌萌计数器(express模块)

![Moe-Counter](https://count.getloli.com/get/@Moe-counter.github)

<details>
<summary>More theme</summary>

##### asoul
![asoul](https://count.getloli.com/get/@demo?theme=asoul)

##### moebooru
![moebooru](https://count.getloli.com/get/@demo?theme=moebooru)

##### rule34
![Rule34](https://count.getloli.com/get/@demo?theme=rule34)

##### gelbooru
![Gelbooru](https://count.getloli.com/get/@demo?theme=gelbooru)</details>

## Demo
[https://count.getloli.com](https://count.getloli.com)

## Usage

### Install

#### Run on Replit

- Open the url [https://replit.com/@journeyad/Moe-Counter](https://replit.com/@journeyad/Moe-Counter)
- Just hit the **Fork** button
- And hit the **Run** button

#### Deploying on your own server

```shell
$ git clone https://github.com/journey-ad/Moe-Counter.git
$ cd Moe-Counter
$ yarn install

$ yarn start
```

#### Run on Vercel

- Click the Button [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/grbnb/moe-counter-vercel/tree/vercel&env=DB_URL,DB_UPSERT,DELAY_SEC,VIEW_LEN&envDescription=🧡💘💖&envLink=https://github.com/grbnb/moe-counter-vercel/tree/vercel#environment-variables)
- Just hit the **Github** button
- Fill in the **Repository Name** blank
- And fill in **environment-variables** value
- Hit the **Deploy** button

### Environment Variables

| Key                | Description                                                                           |
| ------------------ | ------------------------------------------------------------------------------------- |
| DB_URL             | `mongodb+srv://account:passwd@***.***.***.mongodb.net/db_count` **MongoDB login**: [mongodb](https://cloud.mongodb.com)|
| DB_UPSERT          | [Insert new document]`true`or`false`, default=`false`(Update only existing documents) |
| DELAY_SEC          | [Delayed writing to database] set scope `1-180`sec ,default=`60`                      |
| VIEW_LEN           | [Moe-Counter display length] set scope `5-18` , default=`7`                           |

## Credits

*   [replit](https://replit.com/)
*   [A-SOUL_Official](https://space.bilibili.com/703007996)
*   [moebooru](https://github.com/moebooru/moebooru)
*   rule34.xxx NSFW
*   gelbooru.com NSFW
*   [Icons8](https://icons8.com/icons/set/star)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fjourney-ad%2FMoe-Counter?ref=badge_large)
