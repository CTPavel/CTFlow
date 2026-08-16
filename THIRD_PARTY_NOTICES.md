# Сторонние компоненты CTFlow

CTFlow является проприетарным приложением, но включает и использует сторонние компоненты по условиям их собственных лицензий. Этот файл описывает основные компоненты текущих публичных сборок Windows и Android.

## Общие компоненты VPN

### Xray-core

- Windows: Xray-core 26.3.27.
- Android: Xray-core 26.7.28 через XTLS/libXray.
- Проект: [XTLS/Xray-core](https://github.com/XTLS/Xray-core)
- Лицензия: [Mozilla Public License 2.0](https://github.com/XTLS/Xray-core/blob/main/LICENSE)

### XTLS/libXray

- Используется Android-клиентом как мобильная оболочка Xray-core.
- Проект: [XTLS/libXray](https://github.com/XTLS/libXray)
- Лицензия: [MIT](https://github.com/XTLS/libXray/blob/main/LICENSE)

## Windows

### sing-box 1.13.15

- Проект: [SagerNet/sing-box](https://github.com/SagerNet/sing-box)
- Соответствующий upstream-код: [commit 3708fa1](https://github.com/SagerNet/sing-box/tree/3708fa18766cda1f11b77f6ed9c7bd61688f17df)
- Лицензия: [GNU General Public License v3.0 or later](https://github.com/SagerNet/sing-box/blob/dev-next/LICENSE)

### tun2socks 2.6.0

- Проект: [xjasonlyu/tun2socks](https://github.com/xjasonlyu/tun2socks)
- Лицензия: [MIT](https://github.com/xjasonlyu/tun2socks/blob/main/LICENSE)

### Wintun 0.14.1

- Проект: [WireGuard Wintun](https://www.wintun.net/)
- Условия распространения: [официальный репозиторий](https://git.zx2c4.com/wintun/)

### .NET 8

- Проект: [dotnet/runtime](https://github.com/dotnet/runtime)
- Лицензия: [MIT](https://github.com/dotnet/runtime/blob/main/LICENSE.TXT)

## Android

### AndroidX, Jetpack Compose и Material 3

- Проект: [Android Open Source Project / AndroidX](https://android.googlesource.com/platform/frameworks/support/)
- Лицензия: преимущественно [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

### Kotlin и kotlinx

- Используются Kotlin, kotlinx.coroutines и kotlinx.serialization.
- Проект: [Kotlin](https://github.com/JetBrains/kotlin)
- Лицензия: [Apache License 2.0](https://github.com/JetBrains/kotlin/blob/master/license/LICENSE.txt)

## Графика и данные

### Twemoji

Флаги основаны на графике [Twitter Twemoji](https://github.com/twitter/twemoji), лицензия [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

### GeoIP и GeoSite

Наборы правил маршрутизации могут формироваться на основе публичных проектов:

- [v2fly/geoip](https://github.com/v2fly/geoip)
- [v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)

Их состав и лицензии определяются соответствующими upstream-проектами.

## Примечание

Версии выше соответствуют текущим публичным сборкам на дату обновления документа. В состав бинарных зависимостей могут входить транзитивные компоненты под их собственными лицензиями. Тексты лицензий и уведомления upstream имеют преимущественную силу; CTFlow не изменяет права, предоставленные авторами стороннего ПО.
