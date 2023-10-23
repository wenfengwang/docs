# Discord

This documentation will teach you how to integrate your AI into Discord.

Integration is a paid user feature. Therefore, only users with professional subscriptions and above can use integrations.

## How to Setup a Discord Integration

**Prerequisites:**

- Have a [**Discord account**](https://discord.com).

- Have a [**Vanus AI account**](https://ai.vanus.ai).

### Step 1: Create an AI Application

1. Navigate to [**Vanus AI**](https://ai.vanus.ai) and sign in with **Github**, **Google**, **Microsoft Account**① or click **Sign up**②.

![ai_integration_discord1](images/ai_integration_discord1.webp)

2. Initiate a new AI App by hitting the **Create App**③ button.

![ai_integration_discord2](images/ai_integration_discord2.webp)

3. Input an **App Name**④, select an **App Model**⑤, upload to the **Knowledge Base**⑥, then click **Create**⑦.

![ai_integration_discord3](images/ai_integration_discord3.webp)

If you find yourself uncertain about which app model to select, please refer to the [**Large Language Models (LLM) Documentation**](https://docs.vanus.ai/vanus-ai/beginning/large-language-models/) for clear guidance on choosing the most suitable LLM for your requirements.

:::note
In the next steps, we will go to the Discord website or Application to create our Discord Server and get the required credentials to make the connection.
:::

### Step 2: Create a Discord Server

1. Access the Discord App or Webpage at [**Discord**](https://discord.com).

2. After signing in, you can press the **`+`** button to establish a new channel①.

![ai_integration_discord4](images/ai_integration_discord4.webp)

3. Hit **Create My Own**②.

![ai_integration_discord5](images/ai_integration_discord5.webp)

4. Select **For me and my friends**③.

![ai_integration_discord6](images/ai_integration_discord6.webp)

5. Input a **SERVER NAME**④ and click **Create**⑤.

![ai_integration_discord7](images/ai_integration_discord7.webp)

### Step 3: Develop a Discord Application

1. Go to the [**Discord Developer Portal**](https://discord.com/developers/applications).

2. Press **New Application**①.

![ai_integration_discord8](images/ai_integration_discord8.webp)

3. Assign a **NAME**② to your bot, agree to the **Developer Terms of Service and Developer Policy**③, then hit **Create**④.

![ai_integration_discord9](images/ai_integration_discord9.webp)

4. From the sidebar menu, select **Bot**⑤, and under Privileged Gateway Intents, enable **MESSAGE CONTENT INTENT**⑥.

![ai_integration_discord10](images/ai_integration_discord10.webp)

5. Click on **Save Changes**⑦.

![ai_integration_discord11](images/ai_integration_discord11.webp)

6. Press **Reset Token**⑧.

![ai_integration_discord12](images/ai_integration_discord12.webp)

7. **Copy**⑨ the generated token.

![ai_integration_discord13](images/ai_integration_discord13.webp)

8. Return to Vanus AI, click on the **Integrations**⑩ tab and select **Discord Integration**⑪.

![ai_integration_discord14](images/ai_integration_discord14.webp)

9. A **dialog box**⑫ will be displayed on the screen, featuring two blank fields: for a Name and Bot Token.

![ai_integration_discord15](images/ai_integration_discord15.webp)

10. **Name**⑬ the integration, paste the **Bot Token**⑭, and hit **Create**⑮.

![ai_integration_discord16](images/ai_integration_discord16.webp)

11. Your integration has been successfully created and is now **Running**⑯.

![ai_integration_discord17](images/ai_integration_discord17.webp)

12. Finally, to add an AI bot to a channel, return to the application within the developer portal.

13. In the sidebar menu, find **OAuth2**⑰ and **URL Generator**⑱.

![ai_integration_discord18](images/ai_integration_discord18.webp)

14. Choose **bot**⑲ under SCOPES.

![ai_integration_discord19](images/ai_integration_discord19.webp)

15. Under BOT PERMISSION **(ReadMessages/ViewChannel, Send Messages, Mention Everyone, Use External Emojis, Send TTS Messages, Send Messages In threads, Create public, threads Create private threads)** or Administrator.

![ai_integration_discord20](images/ai_integration_discord20.webp)

16. **Copy**⑳ the URL, and then insert it into a web browser to access the authentication page.

![ai_integration_discord21](images/ai_integration_discord21.webp)

17. Choose your **Server**㉑ and press **Continue**㉒.

![ai_integration_discord22](images/ai_integration_discord22.webp)

18. Click on **Authorize**㉓.

![ai_integration_discord23](images/ai_integration_discord23.webp)

19. Your Bot has been successfully **authorized**㉔.

![ai_integration_discord24](images/ai_integration_discord24.webp)

20. Return to your Discord Application or website.

![ai_integration_discord25](images/ai_integration_discord25.webp)

### Communicate with the AI

- To Send a message in a channel, you need to **mention the AI**①.

![ai_integration_discord26](images/ai_integration_discord26.webp)

**Important:** Please be aware that each bot carries a role with a similar name, and trying to mention the role will not yield any results.

![ai_integration_discord27](images/ai_integration_discord27.webp)

- To send a message privately, you can **click on the AI bot**②.

![ai_integration_discord28](images/ai_integration_discord28.webp)

- Write and send your message.

![ai_integration_discord29](images/ai_integration_discord29.webp)

![ai_integration_discord30](images/ai_integration_discord30.webp)
