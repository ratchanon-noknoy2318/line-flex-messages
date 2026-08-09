# Flex Message Examples

|                Telemed Start                |                     More Info                    |                     About Us                     |                    Health Tip                    |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: |
| <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/1_f1m5iv.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/2_ys9ozd.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/5_bitxup.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581211/4_qnspxw.png" width="200"> |
|    [JSON](./TelemedicineStartFlexmessage.json)   |  [JSON](./TelemedicineMoreInfoFlexmessage.json)  |         [JSON](./AboutUsFlexmessage.json)        |       [JSON](./HealthTipsFlexmessage.json)       |


|               Doctor Schedule               |                     Announcements                    |
| :----------------------------------------------: | :----------------------------------------------: |
| <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/3_ltfdkn.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779250757/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_111906_nw7dq3.png" width="200"> |
| [JSON](./ThaiService.json) | [JSON](./AnnouncementsFlexmessage.json) |

---


## Features

* Connect to the LINE Official Account (LINE OA) API
* Send automated notifications (e.g., appointments and registrations)
* Support both push messages and reply messages
* Store data in Google Sheets or a database

---

## Requirements

* Node.js (latest version)
* npm for dependency management
* LINE Messaging API credentials (from the LINE Developers Console)
* Google Sheets API key (if using Google Sheets integration)
* Hosting: Vercel, Netlify, or the hospital's server

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/ratchanon-noknoy2318/line_oa.git
npm install
npm run dev
```

2. Create a `.env` file in the root directory of the project and add the following:

```bash
LINE_CHANNEL_ACCESS_TOKEN=your_line_channel_access_token
LINE_CHANNEL_SECRET=your_line_channel_secret
GOOGLE_SHEETS_API_KEY=your_google_sheets_api_key
PORT=3000
```


---

## Author

**Ratchanon Noknoy**  
- GitHub: [ratchanon-noknoy2318](https://github.com/ratchanon-noknoy2318)  
- LinkedIn: [linkedin.com/in/ratchanon-noknoy](https://linkedin.com/in/ratchanon-noknoy)  
- Role: Solo Software Engineer





