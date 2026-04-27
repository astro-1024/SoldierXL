# SoldierXL

**SoldierXL** is a project to create a specialized LoRA model for generating realistic military personnel.

### Why military?
This niche in Stable Diffusion is still not filled with enough quality content, and basically remains unoccupied. I am a beginner developer, so the project is in the stage of active learning and improvements. There will be errors, experiments, and a search for the ideal balance.

> **Important note:** GitHub has memory limits, so all production "waste," failed iterations, and heavy model weights will be stored on **Hugging Face** or in my **Telegram**, where there will also be just my posts.

---

## 🔗 Links for contact and support
If you want to give advice, help a beginner, or test the developments — write to me!

* **Telegram (main contact):** [ZNB_translate](https://t.me/ZNB_translate)
* **Telegram Channel:** [Channel](https://t.me/+bnwk2qzaHW0yNzli)
* **Hugging Face (main):** [SoldierXL](https://huggingface.co/Zandagabii/SoldierXL)
* **Reddit:** [Link]
* **Discord Community:** [Community](https://discord.gg/nf2FSDsXmy)
* **Discord (rarely active):** `zandagabi_1`

---

## 📜 Version History

### V1.2 (Stable / Current best)
At the moment, this is the most predictable version. It can still produce errors in the geometry of weapons or armor, but it handles the task much better than its predecessors.
*Reason for success: semi-manual dataset tagging.*

| Data | Specification |
| :--- | :--- |
| **Model Base** | RealVisXL V5.0 |
| **Trigger Word** | `rw1soldiers` |
| **Dataset Size** | 296 images |
| **Resolution** | 1024 x 1024 |
| **Training** | 10 Epochs / 2960 Steps |
| **Parameters** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.3 (Experimental / Unstable)
This version was a disappointment, despite doubling the dataset. It confirmed the theory: **data quality is more important than quantity.** The tagging turned out to be unsuccessful, which led to "mush."
*The version is available on Hugging Face and social media for those who want to conduct their own experiments.*

| Data | Specification |
| :--- | :--- |
| **Model Base** | RealVisXL V5.0 |
| **Trigger Word** | `rw0soldiers` |
| **Dataset Size** | 542 images |
| **Resolution** | 1024 x 1024 |
| **Training** | 14 Epochs / 3794 Steps |
| **Parameters** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.0 (Test)
First attempt. The model was undertrained (only 66 images). Currently, the weights are only preserved on Civitai; it is not supported here or anywhere else.

---

**Project Status:** Working 🟢

## ⚠️ Terms of Use and Disclaimer

* **License:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
* **Warning:** This model was created solely for artistic and educational purposes.
* **Prohibited:** Using the model to create propaganda, compromising material, inciting hatred, or for any other malicious purposes.

---
*Developed with enthusiasm and tea. Update for V1.3 with fixed tagging coming soon!*

---
---

# SoldierXL (RU)

**SoldierXL** — это проект по созданию специализированной LoRA модели для генерации реалистичных военных. 

### Почему именно военные?
Эта ниша в Stable Diffusion всё еще недостаточно заполнена качественным контентом, да и в принципе не занята. Я начинающий разработчик, поэтому проект находится в стадии активного обучения и доработок. Здесь будут ошибки, эксперименты и поиск идеального баланса.

> **Важное примечание:** GitHub имеет ограничения по объему памяти, поэтому все «отходы» производства, неудачные итерации и тяжелые веса моделей будут храниться на **Hugging Face** или в моем **Telegram**, где также будут просто мои посты.

---

## 🔗 Ссылки для связи и поддержки
Если вы хотите дать совет, помочь новичку или протестировать наработки — пишите!

* **Telegram (основной канал связи):** [ZNB_translate](https://t.me/ZNB_translate)
* **Telegram Channel:** [Канал](https://t.me/+bnwk2qzaHW0yNzli)
* **Hugging Face (основные):** [SoldierXL](https://huggingface.co/Zandagabii/SoldierXL)
* **Reddit:** [Ссылка]
* **Discord Community:** [Сообщество](https://discord.gg/nf2FSDsXmy)
* **Discord (захожу редко):** `zandagabi_1`

---

## 📜 История версий

### V1.2 (Стабильная / Текущая лучшая)
На данный момент это самая предсказуемая версия. Она все еще может выдавать ошибки в геометрии оружия или брони, но справляется значительно лучше предшественников. 
*Причина успеха: полуручная разметка датасета.*

| Параметр | Значение |
| :--- | :--- |
| **Базовая модель** | RealVisXL V5.0 |
| **Trigger Word** | `rw1soldiers` |
| **Датасет** | 296 изображений |
| **Разрешение** | 1024 x 1024 |
| **Параметры обучения** | 10 Epochs / 2960 Steps |
| **Конфигурация** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.3 (Экспериментальная / Нестабильная)
Эта версия стала разочарованием, несмотря на увеличенный вдвое датасет. Она подтвердила теорию: **качество данных важнее их количества.** Разметка оказалась неудачной, что привело к «каше».
*Версия доступна на Hugging Face и в соцсетях для тех, кто хочет провести свои эксперименты.*

| Параметр | Значение |
| :--- | :--- |
| **Базовая модель** | RealVisXL V5.0 |
| **Trigger Word** | `rw0soldiers` |
| **Датасет** | 542 изображения |
| **Разрешение** | 1024 x 1024 |
| **Параметры обучения** | 14 Epochs / 3794 Steps |
| **Конфигурация** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.0 (Тестовая)
Первая попытка. Модель была недообучена (всего 66 изображений). На данный момент веса сохранились только на Civitai, здесь не поддерживается и негде более.

---

**Статус проекта:** Работает 🟢

## ⚠️ Условия использования и дисклеймер

* **Лицензия:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
* **Предостережение:** Данная модель создана исключительно для художественных и образовательных целей. 
* **Запрещено:** Использовать модель для создания пропаганды, компромата, разжигания ненависти или в любых других противоправных целях.

---
*Разработано с помощью энтузиазма и чая. Скоро будет обновление V1.3 с исправленной разметкой!*
