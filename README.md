A simple multithreaded port scanner built in Python by **Shafique Ahmed** — Ethical Hacker and Computer Science Graduate.

---

## 🚀 Features

- ⚡ Fast TCP port scanning  
- 🎯 Custom port range support  
- 🧵 Multithreaded for better performance  
- 💡 Simple, clean, and beginner-friendly code  

---

## 📦 Requirements

- Python 3.x  
- Works with built-in libraries (`socket`, `threading`, `argparse`)

---

## 📂 Installation

Follow the steps below to set it up and run:

1. **Clone the repository:**
```bash
# Clone the repository from GitHub to your local machine
git clone https://github.com/shafilakho234/python-port-scanner.git

# Change into the newly cloned project directory
cd python-port-scanner

# Check your installed Python version to make sure Python 3 is available
python3 --version
```
---

## 📚 Usage

Run the script using:

```bash
python3 portscanner.py <target> [-p start-end]
```

- `<target>` – The IP address or domain you want to scan (e.g., `127.0.0.1` or `scanme.nmap.org`)
- `[-p start-end]` – *(Optional)* Port range to scan (e.g., `-p 20-100`). If not specified, it will scan common ports.

---

### 💡 Examples

```bash
# Scan localhost with default ports
python3 portscanner.py 127.0.0.1

# Scan a domain with a custom port range
python3 portscanner.py scanme.nmap.org -p 20-100
```
---

## ⚠️ Disclaimer

This tool is created strictly for **educational** and **ethical hacking** purposes.  
**Do not** use it on networks or systems you do not own or have explicit permission to scan.

---

## 🙌 Contributing

Contributions are welcome! If you'd like to improve or extend the tool, feel free to:

1. Fork the repository
2. Create a new branch
3. Submit a pull request

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Shafique Ahmed**  
Ethical Hacker | Computer Science Graduate  
🔗 [GitHub](https://github.com/shafilakho234)


