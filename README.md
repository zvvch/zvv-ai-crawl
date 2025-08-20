# zvv-ai-crawl

> Generative Engine Optimization (GEO) für zvv.ch – Bereitstellung von `llm.txt`, strukturierten JSON-Daten und AI-Crawler-Support, um die Sichtbarkeit des ZVV in LLM-basierten Suchsystemen (ChatGPT, Claude, Perplexity, Arc Search etc.) sicherzustellen.

---

## 🎯 Projektziel

Die Suche verschiebt sich von klassischen Suchmaschinen hin zu **LLM-basierten Answer Engines**.  
Nutzer fragen nicht mehr *„ZVV Ticketpreise“* bei Google, sondern *„Welches Ticket brauche ich von Zürich nach Winterthur?“* in ChatGPT oder Perplexity.  

Ohne Steuerung besteht das Risiko, dass diese Antworten aus **inoffiziellen oder veralteten Quellen** stammen.  
Dieses Projekt sorgt dafür, dass **zvv.ch als „Single Source of Truth“** für generative Suchsysteme indexiert wird.

---

## 📦 Deliverables

- **`llm.txt`**  
  Kuratierte Übersicht der wichtigsten ZVV-Seiten (Markdown-Format).  
  ➝ Für KI-Crawler leicht verständlich, reduziert Fehlinterpretationen.

- **`zvv-llm-data.json`**  
  Strukturierte, maschinenlesbare Daten (Linien, Ticketarten, Tarifzonen, Kontaktinfos).  
  ➝ Ermöglicht präzise Antworten statt Freitext-Deutung.

- **robots.txt Anpassungen**  
  Erlaubt offiziellen AI-Crawlern (z. B. `GPTBot`, `ClaudeBot`, `PerplexityBot`) Zugriff auf die Inhalte.  
  ➝ Verhindert ungewollte Blockaden.

---

## 🛠 Technische Struktur

Alle Dateien werden im **Root-Verzeichnis von zvv.ch** bereitgestellt:

