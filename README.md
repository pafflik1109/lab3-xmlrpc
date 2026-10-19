# ЛР 3

Запуск: xmlrpc_server.ipynb -> xmlrpc_stats2_server.ipynb -> xmlrpc_proxy_server.ipynb -> xmlrpc_client.ipynb.

Порты: 8008, 8009, 8010. Rate limiting: 5 запросов за 5 секунд. При превышении фиксируется too_many_requests, затем запрос выполняется после окончания окна. Недоступность stats-сервера не останавливает основной запрос.
