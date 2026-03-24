# [Nombre de la Máquina]

**Dificultad:** Fácil / Media / Difícil  
**Sistema operativo:** Linux / Windows  
**Fecha:** YYYY-MM-DD  

---

## Resumen

Breve descripción de qué trata la máquina. (2-3 frases)

---

## Reconocimiento

### Escaneo de puertos
```bash
nmap -sV -sC -oN nmap_initial [IP]
```

Hallazgos:
- Puerto X: servicio Y

---

## Explotación

### Vulnerabilidad encontrada

Descripción de qué encontraste y por qué es vulnerable.
```bash
# comandos usados
```

---

## Post-explotación

### Escalada de privilegios
```bash
sudo -l
find / -perm -u=s -type f 2>/dev/null
```

### Flags

- User: `[hash]`
- Root: `[hash]`

---

## Lecciones aprendidas

- Punto 1
- Punto 2
