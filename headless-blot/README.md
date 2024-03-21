

`yarn install`
`sudo apt-get install motion`
`sudo systemctl start motion`
`sudo journalctl -f -u motion`
`sudo mkdir /motion && sudo chown motion:motion /motion`

```
.env requires:

SLACK_BOT_TOKEN=
SLACK_SIGNING_SECRET=
SLACK_APP_TOKEN=
```

motion.conf

- Raspberry Pi
- LCD Writing Tablet
- USB Webcam

(Tablet) <-(rpi-gpio)- (Pi) <-(Motion)-> (Webcam)

(Pi) <-(SerialPort)-> (Blot)

(Pi) <-(Bolt Socket API)-> (Slack)


