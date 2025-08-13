# Purananuru Dataset — Data Dictionary

This document describes the columns in the `purananuru_dataset_v1.0.csv` file.

---

## Column Descriptions

| Column Name | Description |
|-------------|-------------|
| `poem_number` | Sequential number of the poem as per traditional *Purananuru* ordering. |
| `poem_text` | Original Tamil text of the poem, preserved with its metrical structure. |
| `meter` | The metrical form used in the poem (e.g., *Venpa*, *Asiriyappa*). |
| `thinai` | The primary thematic category (*thinai*) of the poem, as per *Puram* genre conventions. |
| `thurai` | The sub-category (*thurai*) within the *thinai*. |
| `sung_for` | The patron, king, or individual in whose honor the poem was sung. |
| `poet` | Name of the poet attributed to the poem. |
| `variant_reading` | Alternate textual readings found in different manuscripts or editions. |
| `english_translation_vaidehi` | English translation of the poem provided by Vaidehi. |
| `english_word_by_word_vaidehi` | Word-by-word English translation provided by Vaidehi. |
| `vaidehi_notes` | Translator’s notes and commentary by Vaidehi. |
| `simple_tamil_rendering` | Simplified modern Tamil rendering for accessibility. |

---

## Notes on Data Structure

- **Text Encoding:** All Tamil text is in Unicode (UTF-8).  
- **Metrical Integrity:** Poem lines and prosodic features are preserved as in the source.  
- **Variant Readings:** Where applicable, differences from the main text are noted in the `variant_reading` column.  
- **Translations:** The English translations aim to be faithful to the source while readable for modern audiences.  

---
