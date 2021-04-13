---
title: Отправка настраиваемых Скибоксес
description: Получите пошаговые инструкции по отправке и устранению неполадок пользовательских скибоксес в Алтспацевр.
ms.date: 03/11/2021
ms.topic: article
keywords: скибоксес, устранение неполадок
ms.openlocfilehash: 02d5bc762dc36d4195100e8155d6250789e833f7
ms.sourcegitcommit: d84a6adf631ff02b106e682238f2861477caef1e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/08/2021
ms.locfileid: "107213265"
---
# <a name="uploading-custom-skyboxes"></a><span data-ttu-id="56580-104">Отправка настраиваемых Скибоксес</span><span class="sxs-lookup"><span data-stu-id="56580-104">Uploading custom Skyboxes</span></span>

<span data-ttu-id="56580-105">Скибокс — это способ создания **фона** для вашего мира, который делает работу более увлекательной.</span><span class="sxs-lookup"><span data-stu-id="56580-105">A Skybox is a way to create a **background** for your World that makes the experience more immersive.</span></span> <span data-ttu-id="56580-106">Существуют различные виды Скибоксес, но сейчас мы поддерживаем **Равнопромежуточная**.</span><span class="sxs-lookup"><span data-stu-id="56580-106">There are different kinds of Skyboxes but we currently support **equirectangular**.</span></span> <span data-ttu-id="56580-107">Вот пример, взятый с камерой 360 [(см. пример):](http://moments.mankindforward.com/)</span><span class="sxs-lookup"><span data-stu-id="56580-107">Here's an example taken with a 360 camera (more example [here](http://moments.mankindforward.com/)):</span></span> 

![360. Равнопромежуточная представление об живущей комнате](images/custom-skyboxes-img-01.jpeg)

<span data-ttu-id="56580-109">Можно также использовать [отправку Unity](world-building-toolkit-getting-started.md) , но такой подход проще.</span><span class="sxs-lookup"><span data-stu-id="56580-109">You can also use the [Unity Uploader](world-building-toolkit-getting-started.md) but this approach is simpler.</span></span>

1. <span data-ttu-id="56580-110">Перейдите к [мировому > скибоксес](https://account.altvr.com/skyboxes) и нажмите кнопку **создать** справа.</span><span class="sxs-lookup"><span data-stu-id="56580-110">Navigate to [Worlds > Skyboxes](https://account.altvr.com/skyboxes) and press the **Create** button on the right</span></span>

![Страница веб-сайта миров, открытая в скибоксес панель](images/custom-skyboxes-img-02.png)

2. <span data-ttu-id="56580-112">Введите имя и укажите свой образ 360.</span><span class="sxs-lookup"><span data-stu-id="56580-112">Fill in a name and specify your 360 image.</span></span> <span data-ttu-id="56580-113">Она не должна быть фотографией, есть программы, которые позволяют рисовать собственные или искать некоторые сети.</span><span class="sxs-lookup"><span data-stu-id="56580-113">It doesn't have to be a photo, there are programs that let you draw your own or you can search for some online.</span></span> <span data-ttu-id="56580-114">Когда будете готовы, нажмите **Создать**.</span><span class="sxs-lookup"><span data-stu-id="56580-114">When you're ready, select **Create**.</span></span> 

![Форма создания скибокс](images/custom-skyboxes-img-03.png)

3. <span data-ttu-id="56580-116">При необходимости можно передать изображение **предварительного просмотра** , чтобы можно было легко найти этот скибокс.</span><span class="sxs-lookup"><span data-stu-id="56580-116">You can optionally upload a **preview** image so you can easily identify this skybox.</span></span> <span data-ttu-id="56580-117">Можно также передать окружающий звук в формате WAV.</span><span class="sxs-lookup"><span data-stu-id="56580-117">You can also upload ambient audio in WAV format.</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="56580-118">Мы рекомендуем отправлять изображения предварительного просмотра и окружающий звук по отдельности после отправки изображения 360.</span><span class="sxs-lookup"><span data-stu-id="56580-118">We recommend you upload preview images and ambient audio separately, after you upload the 360 image.</span></span> <span data-ttu-id="56580-119">Если передать их вместе, размер файлов может быть достаточно большим, чтобы остановлен процесс.</span><span class="sxs-lookup"><span data-stu-id="56580-119">If you upload them together the file sizes can be large enough to stall the process.</span></span> <span data-ttu-id="56580-120">[Жетсонс World](https://account.altvr.com/worlds/1004174988393054363/spaces/1084431533181240311) — отличный пример использования скибокс с окружающими звуками.</span><span class="sxs-lookup"><span data-stu-id="56580-120">[Jetsons World](https://account.altvr.com/worlds/1004174988393054363/spaces/1084431533181240311) is a great example of how to use a Skybox with ambient audio.</span></span> <span data-ttu-id="56580-121">Обратите внимание, что по всему миру не хватает звукового громкости и звуки, которые вы слышите, чтобы люди не могли получить раздражен.</span><span class="sxs-lookup"><span data-stu-id="56580-121">Notice how the World-Builder kept the audio volume low and sounds you hear are sporadic so people don't get annoyed.</span></span> 

4. <span data-ttu-id="56580-122">Введите свой мир и откройте редактор мира.</span><span class="sxs-lookup"><span data-stu-id="56580-122">Enter your World and open the World Editor.</span></span> <span data-ttu-id="56580-123">В разделе Скибоксес выберите новый Скибокс.</span><span class="sxs-lookup"><span data-stu-id="56580-123">Under Skyboxes, select your new Skybox.</span></span> <span data-ttu-id="56580-124">Через несколько секунд значение перевозки будет изменено.</span><span class="sxs-lookup"><span data-stu-id="56580-124">In a few seconds, the sky will literally change.</span></span> <span data-ttu-id="56580-125">Другие пользователи в вашем мире также увидят смену изменений.</span><span class="sxs-lookup"><span data-stu-id="56580-125">Others in your World will also see the sky change.</span></span> <span data-ttu-id="56580-126">Чтобы вернуться назад, выберите скибокс **по умолчанию** в том же списке.</span><span class="sxs-lookup"><span data-stu-id="56580-126">To switch back, choose the **default** skybox in that same list.</span></span> 

## <a name="troubleshooting"></a><span data-ttu-id="56580-127">Устранение неполадок</span><span class="sxs-lookup"><span data-stu-id="56580-127">Troubleshooting</span></span>

<span data-ttu-id="56580-128">**В небесном:-(е есть стык или линия.**</span><span class="sxs-lookup"><span data-stu-id="56580-128">**There's a seam or line in the sky :-(.**</span></span> <span data-ttu-id="56580-129">Это ошибка, которая скоро будет исправлена</span><span class="sxs-lookup"><span data-stu-id="56580-129">It's a bug that we'll fix soon</span></span>

<span data-ttu-id="56580-130">**сбой отправки**</span><span class="sxs-lookup"><span data-stu-id="56580-130">**Upload failed**</span></span>
    * <span data-ttu-id="56580-131">Попробуйте загрузить только образ 360</span><span class="sxs-lookup"><span data-stu-id="56580-131">try uploading just the 360 image on its own</span></span>
    * <span data-ttu-id="56580-132">Попробуйте использовать другой файл меньшего размера в качестве теста</span><span class="sxs-lookup"><span data-stu-id="56580-132">try with another, smaller file as a test</span></span>

<span data-ttu-id="56580-133">**Не удается найти фотографию 360**</span><span class="sxs-lookup"><span data-stu-id="56580-133">**I can't find a 360 photo**</span></span>
    * <span data-ttu-id="56580-134">Flickr — хороший источник (измените фильтры, чтобы найти творческие Commons Attribution).</span><span class="sxs-lookup"><span data-stu-id="56580-134">Flickr is a good source (change the filters to find creative commons ones)</span></span>
    * <span data-ttu-id="56580-135">Сделайте свой собственный!</span><span class="sxs-lookup"><span data-stu-id="56580-135">Take your own!</span></span> <span data-ttu-id="56580-136">Мы успешно выполнили камеры Рикох.</span><span class="sxs-lookup"><span data-stu-id="56580-136">We've had success with Ricoh's cameras.</span></span> 
<span data-ttu-id="56580-137">**Многогранная или блокировка** Может потребоваться найти изображение с более высоким разрешением.</span><span class="sxs-lookup"><span data-stu-id="56580-137">**The sky looks grainy or blocky** You may need to find a higher-resolution image.</span></span> <span data-ttu-id="56580-138">Обычно около 2-5 МБ и ~ 5000 ПКС x 2000 ПКС</span><span class="sxs-lookup"><span data-stu-id="56580-138">Typically around 2-5 MB and ~5000 px x 2000 px</span></span>

<span data-ttu-id="56580-139">**Это вредит в мир!**</span><span class="sxs-lookup"><span data-stu-id="56580-139">**It hurts my World's framerate!**</span></span>
<span data-ttu-id="56580-140">Возможно, изображение слишком велико.</span><span class="sxs-lookup"><span data-stu-id="56580-140">The image is probably too large.</span></span> <span data-ttu-id="56580-141">Некоторые созданные скибоксес могут быть 8 КБ.</span><span class="sxs-lookup"><span data-stu-id="56580-141">Some generated skyboxes can be 8k.</span></span> <span data-ttu-id="56580-142">Обычно они поставляются с удобными для мобильных устройств версиями 2000. Используйте их.</span><span class="sxs-lookup"><span data-stu-id="56580-142">They usually come with mobile-friendly 2k versions--use that.</span></span>

<span data-ttu-id="56580-143">**Помогите мне с окружающими звуками**</span><span class="sxs-lookup"><span data-stu-id="56580-143">**Help me with the ambient audio**</span></span>
    * <span data-ttu-id="56580-144">Используйте бесплатное программное обеспечение, например АудаЦити, чтобы уменьшить объем тома или создать собственные циклы.</span><span class="sxs-lookup"><span data-stu-id="56580-144">Use free software like Audacity to lower the volume or create your own loops.</span></span> <span data-ttu-id="56580-145">Помните, что звук будет повторяться и воспроизводиться в ушкие людей</span><span class="sxs-lookup"><span data-stu-id="56580-145">Remember that the audio will be repeated and playing in people's ears so keep it low and not annoying</span></span>
    * <span data-ttu-id="56580-146">[Бесплатный звук](https://freesound.org/) — хороший источник звуков без проходящих продаж</span><span class="sxs-lookup"><span data-stu-id="56580-146">[Free Sound](https://freesound.org/) is a good source of royalty-free sounds</span></span>
