# Purananuru Dataset — Data Dictionary

This document describes the columns in the `purananuru_dataset_v1.0.csv` file.

---

## Column Descriptions

| Column Name | Description |
|-------------|-------------|
| `poem_number` | Sequential number of the poem as per traditional *Purananuru* ordering. |
| `poem_text` | Original metrically intact Tamil text of the poem. |
| `meter` | The metrical form used in the poem. |
| `thinai` | The primary thematic category (*thinai*) of the poem, as per *Puram* genre conventions. |
| `thurai` | The sub-category(s) (*thurai*) within the *thinai* of the poem. |
| `sung_for` | The patron, king, or individual for whom the poem was sung. |
| `poet` | Name of the poet attributed to the poem. |
| `variant_reading` | Alternate textual readings found in different manuscripts or editions.  |
| `english_translation_vaidehi` | English translation of the poem provided by Vaidehi. |
| `english_word_by_word_vaidehi` | Word-by-word English translation provided by Vaidehi. |
| `vaidehi_notes` | Translator’s notes and commentary by Vaidehi. |
| `simple_tamil_rendering` | Simplified Tamil text of the poem. This undoes the sandhi and meter for easier readibility. |

## Additional Notes

- **Source for Tamil text and metadata:** The `poem_text`, `thinai`, `thurai`, `sung_for`, `poet`, and `variant_reading` fields were scraped from *Purananuru* (U. V. Swaminatha Iyer, 3rd Edition, 1935), available via the Internet Archive: [https://archive.org/details/Tamil-Purananuru-U-Ve-Sa-3rd-Edition-1935/page/n123/mode/1up](https://archive.org/details/Tamil-Purananuru-U-Ve-Sa-3rd-Edition-1935/page/n123/mode/1up).\
\n
- **Source for translations and simplified Tamil renderings:**  
  The `english_translation_vaidehi`, `english_word_by_word_vaidehi`, `vaidehi_notes`, and `simple_tamil_rendering` fields are based on translations and commentaries by Vaidehi, available at:  
  - [Purananuru 1–200](https://sangamtranslationsbyvaidehi.com/ettuthokai-purananuru-1-200/)  
  - [Purananuru 201–400](https://sangamtranslationsbyvaidehi.com/ettuthokai-purananuru-201-400/)  
