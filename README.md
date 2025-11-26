This is an Email Generation and Sending Agent created using OpenAI SDK. It uses gpt-4o-mini as its LLM model.
It has one handoff and three tools which it can access. The handoff itself has access to three other tools which are 
used to generate the emails, pick the best among them and then convert the email to html format.
Twilio's sendgrid is used to send the email.

Here is a sceenshot of the email generated:
<img width="824" height="544" alt="Screenshot 2025-11-26 134827" src="https://github.com/user-attachments/assets/de02bb44-bb11-4efd-aa7d-eff1238fc9a0" />
