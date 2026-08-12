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


## How to Use

1. Copy the JSON code starting from the `content` field onward.
2. Import the copied JSON code into the [Flex Message Simulator](https://account.line.biz/login?redirectUri=https%3A%2F%2Fdevelopers.line.biz%2Fflex-simulator/) website.
3. Click **Send** to test the message.
4. Verify the result before implementing the actual code.
5. Connect the application to the webhook, configure the **LINE Access Token** for authentication, and use [ngrok](https://ngrok.com/) to create a public URL for testing the actual webhook flow.

---
## Security and Incident Management

1. `LINE_CHANNEL_ACCESS_TOKEN` and `LINE_CHANNEL_SECRET` are sensitive information. Do not share them or commit them to GitHub.
2. If the Access Token is leaked or exposed, go to the LINE Developers Console and click **Reissue** to generate a new token immediately.
3. After reissuing the token, update the new value in the `.env` file and restart the server.
4. Use `.gitignore` to prevent the `.env` file from being pushed to GitHub.
5. Monitor logs and notify the relevant team members when a security incident occurs.

---
## Author

**Ratchanon Noknoy**  
- GitHub: [ratchanon-noknoy2318](https://github.com/ratchanon-noknoy2318)  
- LinkedIn: [linkedin.com/in/ratchanon-noknoy](https://linkedin.com/in/ratchanon-noknoy)  
- Role: Solo Software Engineer



