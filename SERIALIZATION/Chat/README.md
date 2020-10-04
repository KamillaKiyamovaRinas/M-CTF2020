# Chat
Мы создали Официальный Чат M*CTF ©, в котором все цтферы могут делиться опытом. Прочитайте флаг из /flag.txt и отправьте нам, чтобы получить золотой цветочек возле имени пользователя.

Чтобы упростить задачу, вот список зависимостей с сервера:

dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-websocket'
    compile group: 'com.esotericsoftware', name: 'kryo', version: '4.0.2'
    compile group: 'org.apache.xbean', name: 'xbean-naming', version: '4.17'
    compileOnly 'org.projectlombok:lombok'
    annotationProcessor 'org.projectlombok:lombok'
}
