import vk
vk_chat_k = 2000000000
vk_bot_id = 329893750

def bot_isLive(m):
	vk_send_message(m, message = randomHint(["Живой", "Жив и цел", "Норм", "Статус: работаю"]))
	return
