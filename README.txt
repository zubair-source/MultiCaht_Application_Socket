OS Project


Group Members:

Muhammad Zubair (f19cscs07)
Muhammad Zain ul Abideen (f19cscs22)

Sample usage through terminal:

(Terminal 1 ->) make
(Terminal 1 ->) ./se 8888 (Start server)
(Terminal 2 ->) ./cl 172.16.24.252 8888 zain (Create unique client)
(Terminal 3 ->) ./cl 172.16.24.252 8888 ali (Create unique client)
(Terminal 4 ->) ./cl 172.16.24.252 8888 ali (Create duplicate client, isn't created)
(Terminal 3 ->) /list (Displays list of clients)
(Terminal 2 ->) /msg zubair hello (Send message to inexistent client from ali)
(Terminal 2 ->) /msg zain hello (Send message to cl3 from ali)
(Terminal 3 ->) /quit (Exit zubair)
(Terminal 2 ->) /list (Check updated list from server)



