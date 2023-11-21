HƯỠNG DẪN KẾT NỐI APP VỚI GITHUB 

1. npm start để chạy app
2. ngrok(sign up ngrok để không bị giới hạn session). command line trong terminal: ngrok http 3000
3. Sau đó sẽ hiện lên ngrok đã chạy thành công. chỗ forwading sẽ có 1 đường link, copy. vào repo github. settings => webhooks => edit payload url. 
NOTE: trong trường hợp không vào được settings repo em thì mn có thể thoải mái tạo repo của riêng mình để thoải mái test, chỉ cần payload URL đúng theo cú pháp. ngroklink/webhook. 
4. Vào postman test thử ở folder Github webhook test xem có connect successful chưa. 
5. Bước cuối, chỉ cần tạo commit trong repo đã connect với app, với cú pháp 
- gì đó #bugid: gì đó 
thì bug sẽ hiện lên comment chứa commit message. 
6. DONE. ở bước nào không được thì hú Lactose Nham, lưu ý để connect được thì local + ngrok phải được chạy.