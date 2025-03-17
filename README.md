<div align="center"><img src="https://raw.githubusercontent.com/limangox/yodmsg/refs/heads/main/img/app.png" width=10%></img>
  
# yodmsg
A CLI tool for Yodel メッセージ app

<a href="#"><img src="https://img.shields.io/badge/license-EULA-yellow" alt="License"></div>

>[!IMPORTANT]
> This is not an open source project, and I make this because I am interested on it.

# Recommended terminal tool (os:win)
> Use the recommended terminal tools to better support the color display of scripts
- Windows Terminal
  - [Mircosoft Store](https://apps.microsoft.com/detail/9n0dx20hk701)
  - [github](https://github.com/microsoft/terminal)
- Cmder : [Homepage](https://cmder.app/)

# How to use

## Save message from all subscription

```
yodmsg -r <refresh_token>
```
> [!NOTE]
> # About `refresh_token`
> * You can use [Proxypin](https://github.com/wanghongenpin/proxypin) to get your ` refresh_token `.


## Save message from specify member

```
yodmsg -r <refresh_token> -m <member_name in japanese>
```

## Save message start from specify date

>[!IMPORTANT]
> This function must with specify member

```
yodmsg -r <refresh_token> -m <member_name in japanese> -t 250317
```

## Download the Thumbnails、voice calling images、offical photos for subscription.

```
yodmsg -r <refresh_token> -p
```

## Query the subscription

```
yodmsg -r <refresh_token> -q
```
