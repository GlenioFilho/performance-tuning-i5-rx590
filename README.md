
# 💻 Performance Tuning: i5-6400 + RX 590 GME

Projeto real de otimização de um PC OEM da Dell com foco em desempenho para jogos como GTA V / FiveM. Foram utilizadas técnicas avançadas de tuning para extrair o máximo do hardware mantendo temperaturas e consumo sob controle.

## 📌 Especificações

- Intel Core i5-6400 @ 3.1 GHz fixo (via ThrottleStop)
- AMD Radeon RX 590 GME (Core: 1380 MHz, Mem: 2000 MHz)
- 16GB DDR3L 1600MHz Dual Channel
- SSD + HDD otimizado
- Placa-mãe Dell OEM

## 🎯 Objetivo

Maximizar o desempenho em jogos com baixo uso de CPU/GPU e estabilidade de FPS. O foco foi remover gargalos de software, configurar o turbo boost, e evitar throttling térmico ou de energia.

## 🔧 Técnicas aplicadas

- Ativação de Turbo Boost fixo via ThrottleStop (3.1GHz)
- Ajuste de voltagem manual segura (~1.10V)
- Ajuste de Power Limits (PL1/PL2 e tempo)
- MSI Afterburner com clocks otimizados
- Adrenalin Software com Radeon Anti-Lag e otimizações
- Desativação de serviços de background do Windows
- Limpeza de cache de shaders
- Temperaturas monitoradas e controladas

## 📊 Resultados

| Métrica                | Antes         | Depois        |
|------------------------|---------------|---------------|
| Clock CPU             | 2.7GHz        | 3.1GHz fixo   |
| FPS médio (GTA V)     | ~45 FPS       | ~60 FPS       |
| Uso da CPU (FiveM)    | ~99% oscilando| ~99% estável  |
| Uso da GPU (FiveM)    | 20-60%        | 80-99%        |
| Temperatura CPU/GPU   | ~38-42 °C     | ~35-38 °C     |
| Estabilidade          | Média         | Alta          |

## 📁 Arquivos incluídos

- `ThrottleStop.ini` — configurações fixas de desempenho
- `prints/` — capturas de CPU-Z, Afterburner, CrystalDiskInfo, etc.

---

Criado por Glenio Filho — QA Engineer | entusiasta de performance & hardware.
