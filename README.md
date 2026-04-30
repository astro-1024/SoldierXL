# SoldierXL

**SoldierXL** is a project to create a specialized LoRA model for generating realistic military personnel.

### Why military?
This niche in Stable Diffusion is still not filled with enough quality content and basically remains unoccupied. I am a beginner developer, so the project is in the stage of active learning and improvements. There will be errors, experiments, and a search for the ideal balance.

> **Important note:** GitHub has memory limits, so all production "waste," failed iterations, and heavy model weights will be stored on **Hugging Face** or in my **Telegram**, where I also post updates.

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

### V1.4 (Stable / Current best)
GOOD NEWS! V1.4 generates images better than all previous generations. During training, I changed the base model to CyberRealistic XL. I believe the final result was improved specifically by the quality of the tagging and the expansion of the dataset.

However, there is a bit of bad news and good news. The bad news is that I have hit a memory limit for training and can no longer expand the dataset locally. But as they say, difficulties breed new solutions. The good news is that I found a resource rental service that accepts crypto. This means you can thank me for creating the model by tossing in a couple of dollars — it would help immensely! I'm not joking; for $1, I can rent a powerful GPU for several hours. If you're interested in how I improved this version, feel free to DM me; I’d love to share and hear your suggestions.

| Parameter | Value |
| :--- | :--- |
| **Model Base** | CyberRealistic XL |
| **Trigger Word** | `rw1soldiers` |
| **Dataset Size** | 996 images |
| **Resolution** | Multi-aspect (1024x1024 to 1536x640) |
| **Training** | 5 Epochs / 4980 Steps |
| **Parameters** | LR 1e-4 / Dim 64 / Alpha 32 |

<img width="1024" height="1024" alt="ComfyUI_temp_jksog_00012_" src="https://github.com/user-attachments/assets/a5cb283d-7bae-47b4-b912-d385a95c37d6" />
<img width="1024" height="1024" alt="ComfyUI_temp_jksog_00030_" src="https://github.com/user-attachments/assets/0b9b6ad3-25b4-4982-9a37-76648a5d4c7c" />
<img width="1024" height="1024" alt="ComfyUI_temp_mxxno_00028_" src="https://github.com/user-attachments/assets/f21ec7dd-40dd-4ee7-a6f4-31e470e13a73" />
<img width="1024" height="1024" alt="ComfyUI_temp_mxxno_00018_" src="https://github.com/user-attachments/assets/cd9de4e8-e350-49d7-8dc9-426b4ed3d321" />

---

### V1.3 (Experimental / Unstable)
This version was a disappointment, despite doubling the dataset. It confirmed the theory: **data quality is more important than quantity.** The tagging turned out to be unsuccessful, which led to "mush."
*The version is available on Hugging Face for those who want to conduct their own experiments.*

| Parameter | Value |
| :--- | :--- |
| **Model Base** | RealVisXL V5.0 |
| **Trigger Word** | `rw0soldiers` |
| **Dataset Size** | 542 images |
| **Resolution** | 1024 x 1024 |
| **Training** | 14 Epochs / 3794 Steps |
| **Parameters** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.2 (Stable / Legacy)
At the moment, this is the most predictable version. It can still produce errors in the geometry of weapons or armor, but it handles the task much better than its predecessors.
*Reason for success: semi-manual dataset tagging.*

| Parameter | Value |
| :--- | : :--- |
| **Model Base** | RealVisXL V5.0 |
| **Trigger Word** | `rw1soldiers` |
| **Dataset Size** | 296 images |
| **Resolution** | 1024 x 1024 |
| **Training** | 10 Epochs / 2960 Steps |
| **Parameters** | LR 1e-4 / Dim 64 / Alpha 32 |

<img width="1024" height="1024" alt="00b8229a-0ed2-40f9-9c18-9808a6df7a2f" src="https://github.com/user-attachments/assets/5f717cd6-5f22-4e97-9669-e91c9da19bc3" />
<img width="1024" height="1024" alt="2a13dde0-fd31-4831-aa30-212d16fdb717" src="https://github.com/user-attachments/assets/72b68464-3ff6-433e-a3ee-953a71e51eda" />
<img width="1024" height="1024" alt="32ac92e4-62f2-4e57-829c-9d21a130021c" src="https://github.com/user-attachments/assets/7c71cd0f-4304-4ca3-8c9f-4aca5cbe8793" />
<img width="1024" height="1024" alt="bef4d177-b961-495f-a53d-409bae2e3d47" src="https://github.com/user-attachments/assets/81d42cd6-3c13-455a-9015-381f612a272e" />

---

### V1.0 (Test)
First attempt. The model was undertrained (only 66 images). Currently, the weights are only preserved on Civitai.

<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/6e16f899-c0dc-4923-85d8-3d3562a854dd" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/d5922832-5065-43a8-ac36-7142d11cca1a" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/f08bca78-5d37-49b8-b815-9ee41a4ab4f4" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/43b99f69-e97c-41aa-8cdd-5344f5b7531b" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/3df2f96f-a5f2-4c84-9971-b6a111f95888" />

---

**Project Status:** Working 🟢

## ⚠️ Terms of Use and Disclaimer

* **License:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
* **Warning:** This model was created solely for artistic and educational purposes.
* **Prohibited:** Using the model to create propaganda, compromising material, inciting hatred, or for any other malicious purposes.

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

### V1.4 (Лучшая / Стабильная)
ХОРОШАЯ НОВОСТЬ! V1.4 генерирует картинки лучше, чем все прошлые поколения. При обучении я изменил родительскую модель на **CyberRealistic XL**. Всё же на итоговый результат, я думаю, повлияло именно качество разметки и расширение датасета. 

Но есть плохая и хорошая новости. Плохая: я уперся в потолок по памяти для обучения, расширять датасет более не могу. Но, как говорится, трудности порождают новые решения. Хорошая новость: я нашел сервис по аренде ресурсов, где можно пополнять баланс криптой. А это значит, что вы можете поблагодарить меня за создание модели, вкинув пару рублей или долларов — это очень сильно мне поможет! Я не шучу: я смогу на 1 доллар арендовать на несколько часов хорошую видеокарту, а чем больше, тем лучше. Если кому-то интересно, как я улучшал эту версию, можете написать в ЛС — я с удовольствием расскажу и заодно послушаю ваши предложения.

| Параметр | Значение |
| :--- | :--- |
| **Базовая модель** | CyberRealistic XL |
| **Trigger Word** | `rw1soldiers` |
| **Датасет** | 996 изображений |
| **Разрешение** | 1024x1024, 832x1216, 1216x832, 768x1344, 1344x768, 704x1280, 1536x640 |
| **Параметры обучения** | 5 Epochs / 4980 Steps |
| **Конфигурация** | LR 1e-4 / Dim 64 / Alpha 32 |

<img width="1024" height="1024" alt="ComfyUI_temp_jksog_00012_" src="https://github.com/user-attachments/assets/a5cb283d-7bae-47b4-b912-d385a95c37d6" />
<img width="1024" height="1024" alt="ComfyUI_temp_jksog_00030_" src="https://github.com/user-attachments/assets/0b9b6ad3-25b4-4982-9a37-76648a5d4c7c" />
<img width="1024" height="1024" alt="ComfyUI_temp_mxxno_00028_" src="https://github.com/user-attachments/assets/f21ec7dd-40dd-4ee7-a6f4-31e470e13a73" />
<img width="1024" height="1024" alt="ComfyUI_temp_mxxno_00018_" src="https://github.com/user-attachments/assets/cd9de4e8-e350-49d7-8dc9-426b4ed3d321" />

---

### V1.3 (Экспериментальная / Нестабильная)
Эта версия стала разочарованием, несмотря на увеличенный вдвое датасет. Она подтвердила теорию: **качество данных важнее их количества.** Разметка оказалась неудачной, что привело к «каше».
*Версия доступна на Hugging Face и в соцсетях для тех, кто хочет провести свои эксперименты. (Все эпохи и версии в Телеграм-канале).*

| Параметр | Значение |
| :--- | :--- |
| **Базовая модель** | RealVisXL V5.0 |
| **Trigger Word** | `rw0soldiers` |
| **Датасет** | 542 изображения |
| **Разрешение** | 1024 x 1024 |
| **Параметры обучения** | 14 Epochs / 3794 Steps |
| **Конфигурация** | LR 1e-4 / Dim 64 / Alpha 32 |

---

### V1.2 (Стабильная / Устаревшая)
На данный момент это самая предсказуемая версия. Она всё еще может выдавать ошибки в геометрии оружия или брони, но справляется значительно лучше предшественников. 
*Причина успеха: полуручная разметка датасета.*

| Параметр | Значение |
| :--- | :--- |
| **Базовая модель** | RealVisXL V5.0 |
| **Trigger Word** | `rw1soldiers` |
| **Датасет** | 296 изображений |
| **Разрешение** | 1024 x 1024 |
| **Параметры обучения** | 10 Epochs / 2960 Steps |
| **Конфигурация** | LR 1e-4 / Dim 64 / Alpha 32 |

Изображения:

<img width="1024" height="1024" alt="00b8229a-0ed2-40f9-9c18-9808a6df7a2f" src="https://github.com/user-attachments/assets/5f717cd6-5f22-4e97-9669-e91c9da19bc3" />
<img width="1024" height="1024" alt="2a13dde0-fd31-4831-aa30-212d16fdb717" src="https://github.com/user-attachments/assets/72b68464-3ff6-433e-a3ee-953a71e51eda" />
<img width="1024" height="1024" alt="32ac92e4-62f2-4e57-829c-9d21a130021c" src="https://github.com/user-attachments/assets/7c71cd0f-4304-4ca3-8c9f-4aca5cbe8793" />
<img width="1024" height="1024" alt="bef4d177-b961-495f-a53d-409bae2e3d47" src="https://github.com/user-attachments/assets/81d42cd6-3c13-455a-9015-381f612a272e" />

---

### V1.0 (Тестовая)
Первая попытка. Модель была недообучена (всего 66 изображений). На данный момент веса сохранились только на Civitai, здесь не поддерживается.

Изображения:

<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/6e16f899-c0dc-4923-85d8-3d3562a854dd" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/d5922832-5065-43a8-ac36-7142d11cca1a" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/f08bca78-5d37-49b8-b815-9ee41a4ab4f4" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/43b99f69-e97c-41aa-8cdd-5344f5b7531b" />
<img width="704" height="1280" alt="изображение" src="https://github.com/user-attachments/assets/3df2f96f-a5f2-4c84-9971-b6a111f95888" />

---

**Статус проекта:** Работает 🟢

## ⚠️ Условия использования и дисклеймер

* **Лицензия:** [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)
* **Предостережение:** Данная модель создана исключительно для художественных и образовательных целей. 
* **Запрещено:** Использовать модель для создания пропаганды, компромата, разжигания ненависти или в любых других противоправных целях.
