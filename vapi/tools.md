# Vapi tools (all POST to n8n webhooks via a tunnel URL)
- bookAppointment(name, phone, service, date, time) -> /webhook/sarah-booking
- cancelAppointment(phone) -> /webhook/sarah-cancel
- rescheduleAppointment(phone, date, time) -> /webhook/sarah-reschedule
- answerQuestion(question) -> /webhook/sarah-faq