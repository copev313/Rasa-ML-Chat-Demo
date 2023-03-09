# Rasa-ML-Chat-Demo
 A demo of the open source ML framework for automating text and voice-based conversations.

-----

### Installing Rasa X

```bash
curl -sSL -o install.sh https://storage.googleapis.com/rasa-x-releases/0.42.6/install.sh
sudo bash ./install.sh
```

```bash
cd /etc/rasa
sudo docker-compose up -d
```

Set admin password:
```bash
cd /etc/rasa
sudo python3 rasa_x_commands.py create --update admin me <PASSWORD>
```

### Default Rasa NLU Model Graph

![Rasa NLU Model Graph]("./app/graph.html")

-----
