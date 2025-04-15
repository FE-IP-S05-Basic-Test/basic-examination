# FE INTERNSHIP 2025 - BASIC EXAMINATION
### Câu 1 (30 point): Phân tích cấu trúc layout có trong design sau:
- Design: https://www.figma.com/design/wMWZYv8gQjBCAZSSuMIzYO/CRM-Dashboard-Customers-List--Community-?node-id=0-1&p=f&t=TfjQwv2nKCQmQ9v9-0
Yêu cầu:
- Phân tích rõ các thành phần chính trong design trên.
- Viết câu trả lời vào file README.md trong thư mục bài làm.
 
### Câu 2 (10 point): Dựng HTML cho section sau:
<img width="1088" alt="Product" src="https://github.com/user-attachments/assets/9d62961b-ae28-4c7a-82d6-c00e81493387" />

Yêu cầu:
- Dựng HTML semantic cho section trên
- Áp dụng best practice: đặt tên class rõ ràng

### Câu 3 (20 point): Áp dụng CSS cho UI ở bài trên (Câu 2)
Yêu cầu:
- Style giống 90% so với UI
- Có hover effect cho các phần tương tác (button, row,…)
- Ưu tiên code rõ ràng, không hardcode quá nhiều

### Câu 4 (40 point): Áp dụng JS để cho phép user tương tác với UI ở bài trên
Cho 1 mảng dữ liệu sau:
```javascript
[
  {
    "customer_name": "Marshall Rodriguez",
    "company_name": "Hegmann",
    "phone_number": "(225) 555-0118",
    "email": "Isai_Champlin52@hotmail.com",
    "country": "Turkey",
    "created_at": "2025-01-21T14:59:18.397Z",
    "deactivated_at": null,
    "id": "1"
  },
  {
    "customer_name": "Roy Swift",
    "company_name": "Dickinson",
    "phone_number": "(302) 555-0107",
    "email": "Micaela_Baumbach@hotmail.com",
    "country": "Burundi",
    "created_at": "2025-03-18T15:53:28.275Z",
    "deactivated_at": "2025-04-13T16:49:45.857Z",
    "id": "2"
  },
  {
    "customer_name": "Preston Aufderhar",
    "company_name": "Lakin",
    "phone_number": "(406) 555-0120",
    "email": "Sigrid.Marvin@yahoo.com",
    "country": "Cyprus",
    "created_at": "2024-06-30T15:02:08.590Z",
    "deactivated_at": "2025-04-14T06:48:01.785Z",
    "id": "3"
  },
  {
    "customer_name": "Gerard Bayer",
    "company_name": "Strosin",
    "phone_number": "(808) 555-0111",
    "email": "Jordon91@yahoo.com",
    "country": "Poland",
    "created_at": "2024-10-19T05:32:08.486Z",
    "deactivated_at": null,
    "id": "4"
  },
  {
    "customer_name": "Kayla Herzog",
    "company_name": "Hansen",
    "phone_number": "(219) 555-0114",
    "email": "Corene.Bergstrom78@gmail.com",
    "country": "United Arab Emirates",
    "created_at": "2024-10-24T07:18:51.934Z",
    "deactivated_at": "2025-04-13T18:24:03.554Z",
    "id": "5"
  },
  {
    "customer_name": "Lloyd Bernier",
    "company_name": "Kreiger",
    "phone_number": "(715) 555-0132",
    "email": "Calista70@yahoo.com",
    "country": "Kiribati",
    "created_at": "2024-10-21T01:01:31.500Z",
    "deactivated_at": null,
    "id": "6"
  },
  {
    "customer_name": "Lynn Renner",
    "company_name": "Funk",
    "phone_number": "(337) 555-0130",
    "email": "Audie.Doyle94@hotmail.com",
    "country": "Uganda",
    "created_at": "2024-11-02T11:11:15.734Z",
    "deactivated_at": "2025-04-13T22:46:29.594Z",
    "id": "7"
  },
  {
    "customer_name": "Darryl Zemlak",
    "company_name": "Stiedemann",
    "phone_number": "(509) 555-0186",
    "email": "Larissa.Dooley@yahoo.com",
    "country": "Peru",
    "created_at": "2024-05-23T16:37:48.857Z",
    "deactivated_at": "2025-04-13T11:20:52.186Z",
    "id": "8"
  },
  {
    "customer_name": "Lillie Pouros",
    "company_name": "Gottlieb",
    "phone_number": "(603) 555-0123",
    "email": "Malika54@hotmail.com",
    "country": "Azerbaijan",
    "created_at": "2024-09-18T14:51:13.127Z",
    "deactivated_at": null,
    "id": "9"
  },
  {
    "customer_name": "Todd Funk",
    "company_name": "Nitzsche",
    "phone_number": "(682) 555-0143",
    "email": "Eleonore65@gmail.com",
    "country": "Kenya",
    "created_at": "2025-01-27T16:40:22.754Z",
    "deactivated_at": "2025-04-14T03:28:04.402Z",
    "id": "10"
  },
  {
    "customer_name": "Bobby Heathcote",
    "company_name": "Farrell",
    "phone_number": "(571) 555-0172",
    "email": "Adella.Batz7@gmail.com",
    "country": "Lesotho",
    "created_at": "2024-07-14T12:20:00.409Z",
    "deactivated_at": null,
    "id": "11"
  },
  {
    "customer_name": "Glenn Reynolds",
    "company_name": "Wisoky",
    "phone_number": "(480) 555-0102",
    "email": "Myrna81@gmail.com",
    "country": "Denmark",
    "created_at": "2024-12-27T20:08:20.347Z",
    "deactivated_at": "2025-04-14T10:09:33.463Z",
    "id": "12"
  },
  {
    "customer_name": "Penny Wilderman",
    "company_name": "Bradtke",
    "phone_number": "(201) 555-0125",
    "email": "Garrison.Carroll71@yahoo.com",
    "country": "Lebanon",
    "created_at": "2024-12-03T23:03:53.746Z",
    "deactivated_at": "2025-04-13T20:32:06.285Z",
    "id": "13"
  },
  {
    "customer_name": "Henrietta Dickens",
    "company_name": "Kerluke",
    "phone_number": "(307) 555-0133",
    "email": "Jeanie50@hotmail.com",
    "country": "Malawi",
    "created_at": "2024-12-24T15:06:03.792Z",
    "deactivated_at": null,
    "id": "14"
  },
  {
    "customer_name": "Sherry Cruickshank",
    "company_name": "Little",
    "phone_number": "(308) 555-0121",
    "email": "Lucious9@hotmail.com",
    "country": "Aland Islands",
    "created_at": "2024-05-04T01:24:16.392Z",
    "deactivated_at": "2025-04-14T04:03:10.200Z",
    "id": "15"
  },
  {
    "customer_name": "Bruce Price",
    "company_name": "Conroy",
    "phone_number": "(512) 555-0110",
    "email": "Don_Sawayn@hotmail.com",
    "country": "Jordan",
    "created_at": "2025-04-08T01:57:46.532Z",
    "deactivated_at": "2025-04-14T05:16:43.999Z",
    "id": "16"
  },
  {
    "customer_name": "Wayne Legros",
    "company_name": "Mante",
    "phone_number": "(907) 555-0167",
    "email": "Patsy94@hotmail.com",
    "country": "Samoa",
    "created_at": "2024-12-30T16:20:16.433Z",
    "deactivated_at": null,
    "id": "17"
  },
  {
    "customer_name": "Erma Lang",
    "company_name": "Hodkiewicz",
    "phone_number": "(202) 555-0127",
    "email": "Sibyl_Doyle77@gmail.com",
    "country": "Armenia",
    "created_at": "2025-03-08T13:53:35.136Z",
    "deactivated_at": "2025-04-13T16:21:56.628Z",
    "id": "18"
  },
  {
    "customer_name": "Sandy Wisoky",
    "company_name": "Thiel",
    "phone_number": "(551) 555-0142",
    "email": "Rafaela.Kuhn47@hotmail.com",
    "country": "Bulgaria",
    "created_at": "2025-03-22T15:55:32.699Z",
    "deactivated_at": "2025-04-14T07:32:46.344Z",
    "id": "19"
  },
  {
    "customer_name": "Jeremy OKon",
    "company_name": "Schultz",
    "phone_number": "(385) 555-0154",
    "email": "Orval_Kertzmann@hotmail.com",
    "country": "French Guiana",
    "created_at": "2024-10-16T20:19:03.919Z",
    "deactivated_at": null,
    "id": "20"
  },
  {
    "customer_name": "Jeff Swift",
    "company_name": "Schamberger",
    "phone_number": "(440) 555-0128",
    "email": "Keyon57@gmail.com",
    "country": "Canada",
    "created_at": "2025-02-20T07:39:23.070Z",
    "deactivated_at": "2025-04-14T06:20:12.393Z",
    "id": "21"
  },
  {
    "customer_name": "Christy King",
    "company_name": "Rempel",
    "phone_number": "(646) 555-0113",
    "email": "Renee11@gmail.com",
    "country": "Russian Federation",
    "created_at": "2024-12-01T11:02:52.415Z",
    "deactivated_at": "2025-04-14T04:43:56.540Z",
    "id": "22"
  },
  {
    "customer_name": "Geoffrey Kuvalis",
    "company_name": "Kutch",
    "phone_number": "(224) 555-0162",
    "email": "Alexanne.Schmitt@yahoo.com",
    "country": "Bhutan",
    "created_at": "2025-01-08T03:58:40.605Z",
    "deactivated_at": null,
    "id": "23"
  },
  {
    "customer_name": "Kathleen Herman",
    "company_name": "Upton",
    "phone_number": "(972) 555-0116",
    "email": "Hannah58@gmail.com",
    "country": "Aruba",
    "created_at": "2024-09-18T00:57:54.699Z",
    "deactivated_at": "2025-04-14T01:22:39.443Z",
    "id": "24"
  },
  {
    "customer_name": "Jana Farrell",
    "company_name": "Lind",
    "phone_number": "(408) 555-0146",
    "email": "Destin_Waters@gmail.com",
    "country": "Croatia",
    "created_at": "2024-11-21T01:20:04.059Z",
    "deactivated_at": "2025-04-13T17:52:07.084Z",
    "id": "25"
  },
  {
    "customer_name": "Dallas Smith",
    "company_name": "Gottlieb",
    "phone_number": "(580) 555-0175",
    "email": "Maxwell59@gmail.com",
    "country": "Greenland",
    "created_at": "2024-10-16T10:51:38.648Z",
    "deactivated_at": null,
    "id": "26"
  },
  {
    "customer_name": "Bob Orn",
    "company_name": "Sawayn",
    "phone_number": "(810) 555-0131",
    "email": "Imogene73@hotmail.com",
    "country": "Norfolk Island",
    "created_at": "2024-04-21T23:35:08.341Z",
    "deactivated_at": "2025-04-14T04:41:50.181Z",
    "id": "27"
  },
  {
    "customer_name": "Troy Barrows",
    "company_name": "Harvey",
    "phone_number": "(347) 555-0129",
    "email": "Leif_Daniel50@yahoo.com",
    "country": "Liechtenstein",
    "created_at": "2024-05-31T01:12:23.429Z",
    "deactivated_at": "2025-04-13T22:45:48.156Z",
    "id": "28"
  },
  {
    "customer_name": "Dolores Kiehn",
    "company_name": "Simonis",
    "phone_number": "(539) 555-0188",
    "email": "Michel_Abbott@gmail.com",
    "country": "Austria",
    "created_at": "2024-07-25T10:52:11.614Z",
    "deactivated_at": null,
    "id": "29"
  },
  {
    "customer_name": "Donna Gottlieb",
    "company_name": "Rath",
    "phone_number": "(410) 555-0156",
    "email": "Leatha_Ryan@gmail.com",
    "country": "Barbados",
    "created_at": "2025-04-05T18:30:35.126Z",
    "deactivated_at": "2025-04-14T04:43:16.455Z",
    "id": "30"
  },
  {
    "customer_name": "Seth Beatty",
    "company_name": "Stiedemann",
    "phone_number": "(740) 555-0177",
    "email": "Christopher54@gmail.com",
    "country": "Estonia",
    "created_at": "2024-12-07T08:55:35.095Z",
    "deactivated_at": "2025-04-13T13:38:19.585Z",
    "id": "31"
  },
  {
    "customer_name": "Edith Kohler",
    "company_name": "Pouros",
    "phone_number": "(316) 555-0119",
    "email": "Dejon.Berge0@gmail.com",
    "country": "Moldova",
    "created_at": "2024-07-20T22:33:47.715Z",
    "deactivated_at": null,
    "id": "32"
  },
  {
    "customer_name": "Winifred Gulgowski",
    "company_name": "Batz",
    "phone_number": "(701) 555-0157",
    "email": "Joseph22@gmail.com",
    "country": "Maldives",
    "created_at": "2024-07-08T06:00:42.285Z",
    "deactivated_at": "2025-04-13T10:50:13.258Z",
    "id": "33"
  },
  {
    "customer_name": "Kathryn Lueilwitz",
    "company_name": "Turner",
    "phone_number": "(618) 555-0161",
    "email": "Bo_Nicolas30@gmail.com",
    "country": "Maldives",
    "created_at": "2024-11-05T17:08:58.562Z",
    "deactivated_at": "2025-04-14T09:58:07.126Z",
    "id": "34"
  },
  {
    "customer_name": "Anita Hartmann",
    "company_name": "Lakin",
    "phone_number": "(319) 555-0151",
    "email": "Ashlynn.Herzog94@yahoo.com",
    "country": "Marshall Islands",
    "created_at": "2024-10-28T09:59:05.940Z",
    "deactivated_at": null,
    "id": "35"
  },
  {
    "customer_name": "Roy Champlin",
    "company_name": "Kreiger",
    "phone_number": "(351) 555-0145",
    "email": "Lincoln_Brown@hotmail.com",
    "country": "Democratic People's Republic of Korea",
    "created_at": "2024-10-31T21:38:46.385Z",
    "deactivated_at": "2025-04-13T18:56:56.663Z",
    "id": "36"
  },
  {
    "customer_name": "Ross Wuckert",
    "company_name": "Stokes",
    "phone_number": "(910) 555-0109",
    "email": "Alicia26@yahoo.com",
    "country": "Ecuador",
    "created_at": "2025-01-13T18:42:02.616Z",
    "deactivated_at": "2025-04-13T22:28:07.958Z",
    "id": "37"
  },
  {
    "customer_name": "Tiffany Miller",
    "company_name": "Goldner",
    "phone_number": "(458) 555-0122",
    "email": "Johnny_Hirthe@yahoo.com",
    "country": "Faroe Islands",
    "created_at": "2025-02-19T15:35:06.948Z",
    "deactivated_at": null,
    "id": "38"
  },
  {
    "customer_name": "Marsha Howe",
    "company_name": "Wintheiser",
    "phone_number": "(863) 555-0103",
    "email": "Kendra.Green@yahoo.com",
    "country": "Democratic Republic of the Congo",
    "created_at": "2025-02-27T23:12:38.811Z",
    "deactivated_at": "2025-04-14T08:48:55.719Z",
    "id": "39"
  },
  {
    "customer_name": "Dwight Rutherford",
    "company_name": "Dach",
    "phone_number": "(240) 555-0179",
    "email": "Ricky.Corkery79@gmail.com",
    "country": "Iran",
    "created_at": "2025-02-03T20:58:58.879Z",
    "deactivated_at": "2025-04-14T06:48:29.054Z",
    "id": "40"
  },
  {
    "customer_name": "Darrel Borer",
    "company_name": "Lindgren",
    "phone_number": "(248) 555-0195",
    "email": "Skye19@yahoo.com",
    "country": "Saint Kitts and Nevis",
    "created_at": "2024-09-02T12:37:19.306Z",
    "deactivated_at": null,
    "id": "41"
  },
  {
    "customer_name": "Lester Schneider",
    "company_name": "Franey",
    "phone_number": "(623) 555-0137",
    "email": "Myrtice.Mosciski-Bayer@gmail.com",
    "country": "Cambodia",
    "created_at": "2024-12-07T03:13:05.492Z",
    "deactivated_at": "2025-04-14T06:53:03.452Z",
    "id": "42"
  },
  {
    "customer_name": "Cecilia Lowe",
    "company_name": "Wilderman",
    "phone_number": "(520) 555-0148",
    "email": "Augustine_Grant18@yahoo.com",
    "country": "Montenegro",
    "created_at": "2025-01-30T02:42:05.464Z",
    "deactivated_at": "2025-04-13T13:40:16.226Z",
    "id": "43"
  },
  {
    "customer_name": "Isabel Kuhic",
    "company_name": "Quigley",
    "phone_number": "(814) 555-0124",
    "email": "Neha62@gmail.com",
    "country": "Russian Federation",
    "created_at": "2025-01-03T12:03:20.972Z",
    "deactivated_at": null,
    "id": "44"
  },
  {
    "customer_name": "Stephanie Jakubowski",
    "company_name": "Runte",
    "phone_number": "(601) 555-0183",
    "email": "Taryn88@hotmail.com",
    "country": "Sudan",
    "created_at": "2024-06-03T04:53:05.670Z",
    "deactivated_at": "2025-04-14T00:04:03.501Z",
    "id": "45"
  },
  {
    "customer_name": "Evan Monahan",
    "company_name": "Breitenberg",
    "phone_number": "(208) 555-0140",
    "email": "Alexa2@gmail.com",
    "country": "Mauritania",
    "created_at": "2024-09-09T07:51:59.269Z",
    "deactivated_at": "2025-04-14T06:26:26.170Z",
    "id": "46"
  },
  {
    "customer_name": "Patricia Wehner",
    "company_name": "Ortiz",
    "phone_number": "(304) 555-0165",
    "email": "Elody.Farrell@gmail.com",
    "country": "Jamaica",
    "created_at": "2024-12-08T22:22:12.447Z",
    "deactivated_at": null,
    "id": "47"
  },
  {
    "customer_name": "Gloria Deckow",
    "company_name": "Jaskolski",
    "phone_number": "(704) 555-0153",
    "email": "Simone.Wisoky54@hotmail.com",
    "country": "Morocco",
    "created_at": "2024-10-22T14:28:36.937Z",
    "deactivated_at": "2025-04-13T21:03:20.393Z",
    "id": "48"
  },
  {
    "customer_name": "Francis Kilback",
    "company_name": "Kihn",
    "phone_number": "(720) 555-0174",
    "email": "Waino.Senger9@yahoo.com",
    "country": "Nauru",
    "created_at": "2024-04-30T13:49:13.153Z",
    "deactivated_at": "2025-04-13T12:24:45.135Z",
    "id": "49"
  },
  {
    "customer_name": "Lance Hahn",
    "company_name": "Quitzon",
    "phone_number": "(270) 555-0136",
    "email": "Dorothy_Lebsack26@yahoo.com",
    "country": "Samoa",
    "created_at": "2024-06-11T17:42:44.712Z",
    "deactivated_at": null,
    "id": "50"
  },
  {
    "customer_name": "Mary Rau",
    "company_name": "Maggio",
    "phone_number": "(405) 555-0134",
    "email": "Jason.Turner8@hotmail.com",
    "country": "Honduras",
    "created_at": "2025-01-07T06:22:27.006Z",
    "deactivated_at": "2025-04-13T13:50:55.154Z",
    "id": "51"
  },
  {
    "customer_name": "Omar Murazik",
    "company_name": "Schultz",
    "phone_number": "(631) 555-0149",
    "email": "Newell19@hotmail.com",
    "country": "Haiti",
    "created_at": "2024-11-07T14:41:33.779Z",
    "deactivated_at": "2025-04-13T19:33:27.471Z",
    "id": "52"
  },
  {
    "customer_name": "Freddie Keeling",
    "company_name": "Zboncak",
    "phone_number": "(470) 555-0164",
    "email": "Alta.Stroman@yahoo.com",
    "country": "Greenland",
    "created_at": "2024-10-21T22:04:32.441Z",
    "deactivated_at": null,
    "id": "53"
  },
  {
    "customer_name": "Lela Murray",
    "company_name": "Rodriguez",
    "phone_number": "(713) 555-0191",
    "email": "Dayton24@gmail.com",
    "country": "Lebanon",
    "created_at": "2024-12-28T06:39:21.792Z",
    "deactivated_at": "2025-04-13T11:28:26.450Z",
    "id": "54"
  },
  {
    "customer_name": "Melba Leannon",
    "company_name": "Corkery",
    "phone_number": "(206) 555-0168",
    "email": "Noble_Ernser53@yahoo.com",
    "country": "Australia",
    "created_at": "2024-12-30T22:36:53.027Z",
    "deactivated_at": null,
    "id": "55"
  }
]
```

Yêu cầu:
- Xử lý đổ dữ liệu vào bảng từ array có sẵn, mỗi trang tối đa 10 records. Nếu có mảng có trên 10 records thì xử lý phân trang như hình (Câu 2).
- Cho phép search theo customer name.
- Có thể sort theo newest, oldest
