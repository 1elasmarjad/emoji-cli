# emoji-cli

Turns a lame commit into a commit with a cool emoji 😎.

![image](https://github.com/user-attachments/assets/32a30206-891e-4c24-80d8-915a20a4766a)

# Steps: Windows
1. Build: go build -o gitmoji.exe emojis.go
2. Move the created emojis.exe into `C:\Windows\System32`
3. Add `EMOJIS_OPENAI_API_KEY` to your systems environment variables
3. Open powershell and run a gitmoji commit, for example: `gitmoji commit -m "Completed user auth"`
4. Done! 🪄 you have now created a commit with an emoji, for example: "🔒 Completed user auth"
