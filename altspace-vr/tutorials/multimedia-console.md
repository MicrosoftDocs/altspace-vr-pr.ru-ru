---
title: Использование консоли мультимедиа
description: Узнайте, как приступить к настройке, публикации и управлению консолью мультимедиа в своих Алтспацеврных впечатлениях.
ms.date: 03/11/2021
ms.topic: article
keywords: консоль, мультимедиа
ms.openlocfilehash: 601328eb6f266dbcfc9d81fc4f1c2d09ac62b318
ms.sourcegitcommit: d84a6adf631ff02b106e682238f2861477caef1e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/08/2021
ms.locfileid: "107212837"
---
# <a name="using-the-multimedia-console"></a><span data-ttu-id="7cec7-104">Использование консоли мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-104">Using the multimedia console</span></span>

<span data-ttu-id="7cec7-105">Консоль мультимедиа — это средство, которое обеспечивает общий доступ к мультимедиа в событиях и мировых средах.</span><span class="sxs-lookup"><span data-stu-id="7cec7-105">The Multimedia Console is a tool that enables media sharing in events and worlds.</span></span> <span data-ttu-id="7cec7-106">Его можно использовать для обмена такими объектами, как изображения, слайды презентации, ливестреамс, видео, списки воспроизведения и многое другое.</span><span class="sxs-lookup"><span data-stu-id="7cec7-106">You can use it to share things like images, presentation slides, livestreams, videos, playlists, and more.</span></span> <span data-ttu-id="7cec7-107">Ниже приведена пошаговая инструкция по использованию мультимедийной консоли **v 0.5.0 +**.</span><span class="sxs-lookup"><span data-stu-id="7cec7-107">Below is a step-by-step instruction on how to use the Multimedia Console **v0.5.0+**.</span></span> 

## <a name="getting-started"></a><span data-ttu-id="7cec7-108">Начало работы</span><span class="sxs-lookup"><span data-stu-id="7cec7-108">Getting started</span></span>

<span data-ttu-id="7cec7-109">Начало работы с консолью мультимедиа состоит из двух этапов.</span><span class="sxs-lookup"><span data-stu-id="7cec7-109">Getting started with the Multimedia Console is a two part process.</span></span>  <span data-ttu-id="7cec7-110">Сначала веб-портал, который будет использоваться для создания и публикации конфигурации для сеанса консоли мультимедиа, размещенного в вашей среде.</span><span class="sxs-lookup"><span data-stu-id="7cec7-110">First there's the web portal that you'll use to generate and publish a configuration for the Multimedia Console session you place in your environment.</span></span>  <span data-ttu-id="7cec7-111">Вторым является размещение приложения консоли мультимедиа в среде и Задание кода конфигурации, который должен использоваться.</span><span class="sxs-lookup"><span data-stu-id="7cec7-111">Second is the placement of the actual Multimedia Console app in your environment and setting the configuration code it should use.</span></span>

### <a name="configuring-the-multimedia-console-with-the-web-portal"></a><span data-ttu-id="7cec7-112">Настройка консоли мультимедиа с помощью веб-портала</span><span class="sxs-lookup"><span data-stu-id="7cec7-112">Configuring the Multimedia console with the web portal</span></span>

1. <span data-ttu-id="7cec7-113">Во-первых, необходимо убедиться в том, что содержимое размещено в сети, так как вам понадобится URL.</span><span class="sxs-lookup"><span data-stu-id="7cec7-113">First, you'll need to make sure your content is hosted online because you'll need a URL.</span></span> <span data-ttu-id="7cec7-114">(Вы можете отправлять фотографии в altvr.com, размещать файл видео в Интернете или использовать ссылку на Твитч Live Stream: https://www.twitch.tv/ninja)</span><span class="sxs-lookup"><span data-stu-id="7cec7-114">(You can upload photos to altvr.com, host a video .mp4 file online or use Twitch live stream link: https://www.twitch.tv/ninja)</span></span> 
2. <span data-ttu-id="7cec7-115">Перейдите на веб-портал для консоли мультимедиа по адресу [https://multimedia-console.altvr.com/](https://multimedia-console.altvr.com/)</span><span class="sxs-lookup"><span data-stu-id="7cec7-115">Navigate to the web portal for the Multimedia Console at [https://multimedia-console.altvr.com/](https://multimedia-console.altvr.com/)</span></span>
3. <span data-ttu-id="7cec7-116">На веб-портале можно создать и опубликовать конфигурацию для консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-116">From the web portal, you can generate and publish a configuration for the Multimedia Console.</span></span>  <span data-ttu-id="7cec7-117">(Дополнительные сведения о различных свойствах см. ниже.)</span><span class="sxs-lookup"><span data-stu-id="7cec7-117">(See below for details about the various properties).</span></span>
4. <span data-ttu-id="7cec7-118">После того как вы ввели носитель в список носителей и настроили общие параметры, нажмите кнопку Опубликовать в правой верхней части приложения.</span><span class="sxs-lookup"><span data-stu-id="7cec7-118">Once you've entered the media into the media list and have configured the general settings, select the publish button in the top-right part of the app.</span></span>
5. <span data-ttu-id="7cec7-119">После завершения публикации появится диалоговое окно с двумя текстовыми файлами для входа в консоль мультимедиа, которую вы поместили.</span><span class="sxs-lookup"><span data-stu-id="7cec7-119">Once the publish has completed, a dialog will pop up with a two word code for you to enter in to the Multimedia Console you placed.</span></span>
  
### <a name="placing-the-multimedia-console-in-your-environment"></a><span data-ttu-id="7cec7-120">Размещение консоли мультимедиа в своей среде</span><span class="sxs-lookup"><span data-stu-id="7cec7-120">Placing the Multimedia console in your environment</span></span>

1. <span data-ttu-id="7cec7-121">Выберите на **> редакторе мира панель редактора > приложения пакета SDK > консоль мультимедиа**.</span><span class="sxs-lookup"><span data-stu-id="7cec7-121">Select on **World Editor > Editor Panel > SDK Apps > Multimedia Console**.</span></span> <span data-ttu-id="7cec7-122">(Не переходите в **мир > основы > приложение пакета SDK**— это для незарегистрированных приложений.)</span><span class="sxs-lookup"><span data-stu-id="7cec7-122">(Don't go to **World Editor > Basics > SDK App**--that's for unregistered apps.)</span></span>  
2. <span data-ttu-id="7cec7-123">Разместите консоль мультимедиа для лучшего набора своих сфер и аудитории.</span><span class="sxs-lookup"><span data-stu-id="7cec7-123">Position the Multimedia Console to best suite your space and audience.</span></span>
3. <span data-ttu-id="7cec7-124">Чтобы выйти из режима редактирования, нажмите кнопку "оранжевый режим изменения".</span><span class="sxs-lookup"><span data-stu-id="7cec7-124">Get out of Edit Mode by clicking the orange Edit Mode button.</span></span>
4. <span data-ttu-id="7cec7-125">Вам будет предложено сделать **вас владельцем проигрывателя мультимедиа?**</span><span class="sxs-lookup"><span data-stu-id="7cec7-125">You'll be prompted **Are you the media player owner?**</span></span> <span data-ttu-id="7cec7-126">Если вы являетесь пользователем, который является официальным владельцем этого сеанса консоли мультимедиа, подтвердите его и продолжайте.</span><span class="sxs-lookup"><span data-stu-id="7cec7-126">If you're the person who should be the official owner of this Multimedia Console session, confirm and continue.</span></span> <span data-ttu-id="7cec7-127">(Также доступны и другие разрешения ролей.</span><span class="sxs-lookup"><span data-stu-id="7cec7-127">(Other permissioned roles are available as well.</span></span> <span data-ttu-id="7cec7-128">Подробный список см. ниже.)</span><span class="sxs-lookup"><span data-stu-id="7cec7-128">See below for a detailed list.)</span></span>
5. <span data-ttu-id="7cec7-129">Выберите Да, чтобы подтвердить, что вы являетесь основным узлом.</span><span class="sxs-lookup"><span data-stu-id="7cec7-129">Select Yes to confirm that you are the primary host.</span></span>  
6. <span data-ttu-id="7cec7-130">Откроется диалоговое окно с запросом на ввод кода с веб-портала или допустимого JSON.</span><span class="sxs-lookup"><span data-stu-id="7cec7-130">A dialog should pop up that asks you to enter a code from the web portal or valid JSON.</span></span>  <span data-ttu-id="7cec7-131">Введите два слова на веб-портале, включая тире, и нажмите кнопку ОК.</span><span class="sxs-lookup"><span data-stu-id="7cec7-131">Enter the two word code from the web portal including the dash and hit OK.</span></span> <span data-ttu-id="7cec7-132">(JSON — это расширенная конфигурация, описанная ниже).</span><span class="sxs-lookup"><span data-stu-id="7cec7-132">(JSON is an advanced configuration described below)</span></span>
7. <span data-ttu-id="7cec7-133">Консоль мультимедиа должна быть загружена через несколько секунд с конфигурацией, созданной на веб-портале.</span><span class="sxs-lookup"><span data-stu-id="7cec7-133">The Multimedia Console should load after a few seconds with the configuration you built in the web portal.</span></span>

### <a name="controlling-the-multimedia-console"></a><span data-ttu-id="7cec7-134">Управление консолью мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-134">Controlling the Multimedia console</span></span>

1. <span data-ttu-id="7cec7-135">После ввода кода и завершения процесса настройки вы увидите, что кнопки управления отображаются под медиа-дисплеем.</span><span class="sxs-lookup"><span data-stu-id="7cec7-135">After you input your code and complete the configuration process, you'll see control buttons appear below a media display.</span></span> 
    * <span data-ttu-id="7cec7-136">**Воспроизвести** запускает средство просмотра мультимедиа (или перезапускается в текущей записи, если ранее она была остановлена).</span><span class="sxs-lookup"><span data-stu-id="7cec7-136">**Play** starts the media viewer (or restarts at current entry, if previously stopped)</span></span> 
    * <span data-ttu-id="7cec7-137">**Остановить** останавливает средство просмотра мультимедиа и скрывает Текущий носитель.</span><span class="sxs-lookup"><span data-stu-id="7cec7-137">**Stop** stops the media viewer, and hides current media.</span></span>  
    * <span data-ttu-id="7cec7-138">**Следующий/** предыдущий переход к следующему или предыдущему носителю</span><span class="sxs-lookup"><span data-stu-id="7cec7-138">**Next/Prev** skips to next or previous media</span></span> 
    * <span data-ttu-id="7cec7-139">**x/x**   показывает текущий индекс в списке носителей и позволяет перейти к любой точке в списке</span><span class="sxs-lookup"><span data-stu-id="7cec7-139">**x/x** shows the current index into the media list, and allows you to jump to any point in the list</span></span>
    * <span data-ttu-id="7cec7-140">**Config** позволяет повторно ввести новый код с веб-портала, чтобы задать новую конфигурацию в консоли.</span><span class="sxs-lookup"><span data-stu-id="7cec7-140">**Config** allows reentering a new code from the web portal to set a new configuration in the console.</span></span> 

<span data-ttu-id="7cec7-141">Теперь вы настроили начало совместного использования через консоль мультимедиа!</span><span class="sxs-lookup"><span data-stu-id="7cec7-141">Now you're set to begin sharing via the Multimedia Console!</span></span>  
 
## <a name="working-with-the-web-portal"></a><span data-ttu-id="7cec7-142">Работа с веб-порталом</span><span class="sxs-lookup"><span data-stu-id="7cec7-142">Working with the web portal</span></span>

<span data-ttu-id="7cec7-143">Веб-портал — это веб-приложение, которое позволяет настраивать различные функции консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-143">The web portal is a web app that enables configuring the various features of the Multimedia Console.</span></span>  <span data-ttu-id="7cec7-144">Эти функции подразделяются на две категории. Общие параметры консоли мультимедиа и список воспроизведения мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-144">These features fall in to two categories; general media console settings, and the media play list.</span></span>

### <a name="multimedia-console-general-settings"></a><span data-ttu-id="7cec7-145">Общие параметры консоли мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-145">Multimedia console general settings</span></span>

<span data-ttu-id="7cec7-146">**Playback Settings**</span><span class="sxs-lookup"><span data-stu-id="7cec7-146">**Playback Settings**</span></span>

<span data-ttu-id="7cec7-147">Общие параметры воспроизведения для списка носителей</span><span class="sxs-lookup"><span data-stu-id="7cec7-147">General playback settings for the media list</span></span>

* <span data-ttu-id="7cec7-148">**Список носителей циклов**— определяет, должен ли список носителей прокручиваться сразу после достижения конца списка.</span><span class="sxs-lookup"><span data-stu-id="7cec7-148">**Loop Media List**- Determines whether the media list should loop around once you reach the end of the list.</span></span>
* <span data-ttu-id="7cec7-149">**Метод Start** — выбирает метод запуска консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-149">**Start Method** - Selects the method by which the multimedia console should start.</span></span>
    * <span data-ttu-id="7cec7-150">Ручная — Ожидание нажатия кнопки воспроизведения перед запуском мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-150">Manual - Waits for the play button to be pressed before starting the media</span></span>
    * <span data-ttu-id="7cec7-151">Автоматический запуск с начала — автоматический запуск списка носителей с начала списка</span><span class="sxs-lookup"><span data-stu-id="7cec7-151">Auto Start from Beginning - Auto start the media list from the beginning of the list</span></span>
    * <span data-ttu-id="7cec7-152">Автоматический запуск случайным образом запускает носитель с произвольной начальной точки в списке</span><span class="sxs-lookup"><span data-stu-id="7cec7-152">Auto Start Random - Auto starts the media from a random starting point in the list</span></span>

<span data-ttu-id="7cec7-153">**Роли**</span><span class="sxs-lookup"><span data-stu-id="7cec7-153">**Roles**</span></span>

<span data-ttu-id="7cec7-154">Назначения ролей для управления и настройки консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-154">Role assignments for controlling and configuring the Multimedia Console.</span></span>    <span data-ttu-id="7cec7-155">Эти роли разбиваются на следующие наборы:</span><span class="sxs-lookup"><span data-stu-id="7cec7-155">These roles are broken down in to the following set:</span></span>

* <span data-ttu-id="7cec7-156">**Только владелец** — пользователь, являющийся владельцем сеанса консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-156">**Owner Only** - The user that is the owner of the Multimedia Console Session</span></span>
* <span data-ttu-id="7cec7-157">Пользователи с **повышенными правами** — пользователи, имеющие роли модератора, ведущего или выступающего в пространстве, настроенном в первоначальной консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-157">**Elevated Users** - Users that have moderator, host, or presenter roles in the space that the Multimedia Console is configured in originally</span></span>
* <span data-ttu-id="7cec7-158">**Все пользователи** — все пользователи</span><span class="sxs-lookup"><span data-stu-id="7cec7-158">**All Users** - All users</span></span>

<span data-ttu-id="7cec7-159">Эти роли помещаются в том смысле, что все роли выше, выбранные в этом списке, также получат разрешение на использование этой функции.</span><span class="sxs-lookup"><span data-stu-id="7cec7-159">These roles stack in the sense that all roles above the one chosen in this list will also be granted permission to use that feature.</span></span>  <span data-ttu-id="7cec7-160">Пример: **Пользователи с повышенными привилегиями** включают **владельца** , даже если они не являются модератором, узлом или выступающим \* \* в алтспацевр.</span><span class="sxs-lookup"><span data-stu-id="7cec7-160">Example: **Elevated Users** includes the **Owner** even if they aren't a moderator, host, or presenter\*\* in AltspaceVR.</span></span> <span data-ttu-id="7cec7-161">Ниже перечислены функции, контролируемые назначениями ролей.</span><span class="sxs-lookup"><span data-stu-id="7cec7-161">Features that are controlled by role assignments are as follows</span></span>

* <span data-ttu-id="7cec7-162">**Может управлять проигрывателем мультимедиа** — определяет, какие роли могут управлять кнопками воспроизведения мультимедиа для консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-162">**Can control media player** - Determines what roles can control the media playback buttons for the Multimedia Console</span></span>
* <span data-ttu-id="7cec7-163">**Можно настроить проигрыватель мультимедиа** . определяет, какие роли могут настраивать консоль мультимедиа, путем предоставления доступа к кнопке **конфигурации** .</span><span class="sxs-lookup"><span data-stu-id="7cec7-163">**Can configure the media player** - Determines what roles can configure the Multimedia Console by being granted access to the **Config** button</span></span>

### <a name="adding-photos-and-videos-to-the-media-list"></a><span data-ttu-id="7cec7-164">Добавление фотографий и видео в список мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-164">Adding photos and videos to the media list</span></span>

<span data-ttu-id="7cec7-165">Носитель — это сердце консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-165">Media is the heart of the Multimedia Console.</span></span>  <span data-ttu-id="7cec7-166">Изображения и ссылки на видео поддерживаются как типы мультимедиа в консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-166">Images and video links are supported as media types within the Multimedia Console.</span></span>  <span data-ttu-id="7cec7-167">Чтобы добавить новый носитель, выберите значок **Добавить изображение** или **добавить значки видео** , чтобы открыть диалоговое окно для ввода сведений о файлах мультимедиа и параметров.</span><span class="sxs-lookup"><span data-stu-id="7cec7-167">To add new media, select either the **Add Image** or **Add Video** icons to have a dialog pop up to enter the media information and settings.</span></span>  <span data-ttu-id="7cec7-168">Ниже приведена классификация типов мультимедиа и связанных с ними параметров.</span><span class="sxs-lookup"><span data-stu-id="7cec7-168">Below is the breakdown of the media types and associated settings</span></span>

<span data-ttu-id="7cec7-169">**Изображение**</span><span class="sxs-lookup"><span data-stu-id="7cec7-169">**Image**</span></span>

<span data-ttu-id="7cec7-170">Изображения должны быть стандартными типами изображений, такими как JPEG, PNG и наверх.</span><span class="sxs-lookup"><span data-stu-id="7cec7-170">Images should be a standard image type such as jpeg, png, and son on.</span></span> <span data-ttu-id="7cec7-171">Они должны размещаться в любом месте с общедоступной ссылкой.</span><span class="sxs-lookup"><span data-stu-id="7cec7-171">They need to be hosted somewhere with a public link.</span></span>

* <span data-ttu-id="7cec7-172">**Имя — (** обязательно) имя, с которым нужно указать образ.</span><span class="sxs-lookup"><span data-stu-id="7cec7-172">**Name** - (Required) Name that you wish to identify the image with.</span></span>
* <span data-ttu-id="7cec7-173">**URL-адрес изображения** — (обязательно) общедоступный URL-адрес изображения</span><span class="sxs-lookup"><span data-stu-id="7cec7-173">**Image URL** - (Required) The public url of the image</span></span>
* <span data-ttu-id="7cec7-174">**Пропускать после** — количество секунд, в течение которых изображение должно быть пропущено после</span><span class="sxs-lookup"><span data-stu-id="7cec7-174">**Skip After** - The number of seconds that the image should be skipped after</span></span>

<span data-ttu-id="7cec7-175">**Видео**</span><span class="sxs-lookup"><span data-stu-id="7cec7-175">**Video**</span></span>

<span data-ttu-id="7cec7-176">Видео могут быть размещенными видео или интерактивными потоками через Твитч и Дливе.</span><span class="sxs-lookup"><span data-stu-id="7cec7-176">Videos can be hosted videos or live streams through Twitch and DLive.</span></span>  <span data-ttu-id="7cec7-177">(Другая поддержка может работать с дополнительной работой для получения соответствующего URL-адреса потока, но не полностью поддерживается в консоли мультимедиа).</span><span class="sxs-lookup"><span data-stu-id="7cec7-177">(Other support may function with extra work to get the proper stream url, but aren't fully supported within the Multimedia Console)</span></span>

* <span data-ttu-id="7cec7-178">**Имя — (** обязательно) имя, с которым вы хотите опознать видео.</span><span class="sxs-lookup"><span data-stu-id="7cec7-178">**Name** - (Required) Name that you wish to identify the video with.</span></span>
* <span data-ttu-id="7cec7-179">**URL-адрес видео** — (обязательный) общедоступный URL-адрес, на котором размещается видео, или поток, из которого он обрабатывается.</span><span class="sxs-lookup"><span data-stu-id="7cec7-179">**Video URL** - (Required) The public url that the video is hosted at or the live stream is served from.</span></span>
* <span data-ttu-id="7cec7-180">**Пропускать после** — количество секунд, в течение которых видео должно быть пропущено после</span><span class="sxs-lookup"><span data-stu-id="7cec7-180">**Skip After** - The number of seconds that the video should be skipped after</span></span>
* <span data-ttu-id="7cec7-181">**Том** — объем видео в диапазоне от 0 (мин) до 1 (максимум).</span><span class="sxs-lookup"><span data-stu-id="7cec7-181">**Volume** - The volume of the video from 0 (min) - 1 (max) values.</span></span>
* <span data-ttu-id="7cec7-182">**Время начала** — количество секунд с начала видео.</span><span class="sxs-lookup"><span data-stu-id="7cec7-182">**Start Time** - The number of seconds from the beginning of the video start from.</span></span>
* <span data-ttu-id="7cec7-183">**Начальное расстояние начала** — расстояние в метрах в мире, на которое начинается отключение тома при переходе с консоли мультимедиа</span><span class="sxs-lookup"><span data-stu-id="7cec7-183">**Roll Off Start Distance** - The distance in meters in world that the volume begins to fall off at as you move away from the Multimedia Console</span></span>
* <span data-ttu-id="7cec7-184">**Действие при завершении видео** — действие, которое будет выполнено после окончания этого видео.</span><span class="sxs-lookup"><span data-stu-id="7cec7-184">**End of Video Action** - The action to take once the end of the video is reached.</span></span>
    * <span data-ttu-id="7cec7-185">Остановить — список носителей останавливается после завершения видео</span><span class="sxs-lookup"><span data-stu-id="7cec7-185">Stop - The media list stops after the video has ended</span></span>
    * <span data-ttu-id="7cec7-186">Цикл — видео пройдет цикл до тех пор, пока не будет пропущено вручную</span><span class="sxs-lookup"><span data-stu-id="7cec7-186">Loop - The video will loop until manually skipped</span></span>
    * <span data-ttu-id="7cec7-187">Воспроизвести далее. следующий носитель в списке носителей будет запущен после окончания текущего видео.</span><span class="sxs-lookup"><span data-stu-id="7cec7-187">Play Next - The next media in the media list will be started after the current video ends.</span></span>

## <a name="working-with-json-directly-advancedoptional"></a><span data-ttu-id="7cec7-188">Непосредственная работа с JSON (дополнительно или необязательно)</span><span class="sxs-lookup"><span data-stu-id="7cec7-188">Working with JSON directly (advanced/optional)</span></span>

<span data-ttu-id="7cec7-189">Консоль мультимедиа поддерживает ввод JSON непосредственно в запрос консоли в Алтспацевр.</span><span class="sxs-lookup"><span data-stu-id="7cec7-189">The Multimedia Console supports entering JSON directly in to the prompt of the console in AltspaceVR.</span></span>  <span data-ttu-id="7cec7-190">JSON — это внутренний механизм, с помощью которого мы включили конфигурации проигрывателя мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-190">JSON is the internal mechanism with which we enable media player configurations.</span></span> <span data-ttu-id="7cec7-191">Предоставление возможности непосредственного задания JSON — это то, что позволяет более опытным пользователям создавать собственные рабочие процессы, которые задают свои потребности и знакомство с JSON.</span><span class="sxs-lookup"><span data-stu-id="7cec7-191">Exposing the ability to set JSON directly is something that allows for more advanced users to build their own workflows that suites their needs and familiarity with JSON.</span></span>  <span data-ttu-id="7cec7-192">Ниже приведено краткое описание структуры JSON и схемы, с помощью которой проверяется JSON-код.</span><span class="sxs-lookup"><span data-stu-id="7cec7-192">The following is a brief description of the JSON structure and the schema by which the JSON is validated.</span></span> <span data-ttu-id="7cec7-193">Более подробное описание приведенных ниже свойств см. в разделах, посвященных настройке консоли мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="7cec7-193">For more detailed descriptions of the properties below, see the above sections that talk about configuring the Multimedia Console.</span></span>  <span data-ttu-id="7cec7-194">В этом разделе основное внимания уделяется примерам схемы и структурированию данных JSON.</span><span class="sxs-lookup"><span data-stu-id="7cec7-194">This section is focused primarily on the schema examples and structuring for the JSON data.</span></span>

### <a name="global-media-settings"></a><span data-ttu-id="7cec7-195">Глобальные параметры носителя</span><span class="sxs-lookup"><span data-stu-id="7cec7-195">Global media settings</span></span>

```json
{
  "loopMediaList": true | false
  "startMethod": "manual" | "autostart-beginning" | "autostart-random"
  "controlMediaPlayer": "everyone" | "elevated" | "owner"
  "configureMediaPlayer": "elevated" | "owner"
  ...
}
```

### <a name="media-list"></a><span data-ttu-id="7cec7-196">Список носителей</span><span class="sxs-lookup"><span data-stu-id="7cec7-196">Media list</span></span>

<span data-ttu-id="7cec7-197">Список носителей — это свойство, заданное в корне структуры JSON, например роли и параметры воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="7cec7-197">The media list is a property set at the root of the JSON structure like the Roles and Playback Settings.</span></span>  <span data-ttu-id="7cec7-198">Это простой массив, который может содержать одну из следующих структур конфигурации носителя.</span><span class="sxs-lookup"><span data-stu-id="7cec7-198">It's a simple array that can contain one of the following media configuration structures.</span></span> <span data-ttu-id="7cec7-199">(Дополнительные сведения о том, что они представляют, см. в описании свойств выше).</span><span class="sxs-lookup"><span data-stu-id="7cec7-199">(See property descriptions above for details on what each does.)</span></span>

<span data-ttu-id="7cec7-200">**Пример изображения**</span><span class="sxs-lookup"><span data-stu-id="7cec7-200">**Image example**</span></span>

<span data-ttu-id="7cec7-201">*Обязательные поля: "Name" и "imageUrl"*</span><span class="sxs-lookup"><span data-stu-id="7cec7-201">*Required fields: "name" and "imageUrl"*</span></span>

```json
{
    "name": "Altspace Screenshot",
    "imageUrl": "https://pbs.twimg.com/media/CxJ-fJqUsAAFtd9.jpg",
    "skipAfter": 10
}
```

<span data-ttu-id="7cec7-202">**Пример видео**</span><span class="sxs-lookup"><span data-stu-id="7cec7-202">**Video example**</span></span>

<span data-ttu-id="7cec7-203">*Обязательные поля: "Name" и "Видеаурл"*</span><span class="sxs-lookup"><span data-stu-id="7cec7-203">*Required fields: "name" and "videoUrl"*</span></span>

```json
{
    "name": "Ninja Twitch Live Stream",
    "videoUrl":"https://www.twitch.tv/ninja",
    "volume":0.2,
    "startTime":0,
    "endOfVideoAction":"play-next"
}
```

### <a name="example-json"></a><span data-ttu-id="7cec7-204">Пример JSON</span><span class="sxs-lookup"><span data-stu-id="7cec7-204">Example JSON</span></span>

```json
{
  "loopMediaList": false,
  "startMethod": "autostart-beginning",
  "controlMediaPlayer": "everyone",
  "configureMediaPlayer": "elevated",
  "mediaList": [
    {
      "videoUrl": "https://www.twitch.tv/ninja",
      "volume": 0.2,
      "startTime": 0,
      "endOfVideoAction": "play-next"
    },
    {
      "imageUrl": "http://www.hypergridbusiness.com/wp-content/uploads/2016/09/AltspaceVR-highrise.jpg",
      "skipAfter": 10
    },
    {
      "imageUrl": "https://d1qb2nb5cznatu.cloudfront.net/startups/i/333629-6ffd7199b9bcf34d8957e8e09d974a38-medium_jpg.jpg?buster=1423092095",
      "skipAfter": 5
    },
    {
      "imageUrl": "https://pbs.twimg.com/media/CxJ-fJqUsAAFtd9.jpg",
      "skipAfter": 10
    },
    {
      "imageUrl": "https://altvr-wpengine.netdna-ssl.com/wp-content/uploads/2019/05/Educators-in-VR-Social-VR-AltspaceVR.png",
      "skipAfter": 10
    },
    {
      "videoUrl": "https://www.twitch.tv/shroud",
      "volume": 1,
      "startTime": 0,
      "endOfVideoAction": "stop"
    }
  ]
}
```

### <a name="schema"></a><span data-ttu-id="7cec7-205">схема</span><span class="sxs-lookup"><span data-stu-id="7cec7-205">Schema</span></span>

```json
{
  "$schema": "https://json-schema.org/draft-04/schema#",
  "type": "object",
  "required": [
    "mediaList"
  ],
  "properties": {
    "loopMediaList": {
      "type": "boolean",
      "description": "Whether to loop through the media list when reaching the beginning or end of the list."
    },
    "controlMediaPlayer": {
      "type": "string",
      "enum": [
        "everyone",
        "elevated",
        "owner"
      ],
      "default": "owner",
      "description": "What roles are able to control the media player. (Owner can always control player)"
    },
    "configureMediaPlayer": {
      "type": "string",
      "enum": [
        "elevated",
        "owner"
      ],
      "default": "owner",
      "description": "What roles are allowed to configure the media play list.  Note: This role needs to be able to control the media player in order to configure it. (Owner can always configure media)"
    },
    "startMethod": {
      "type": "string",
      "enum": [
        "manual",
        "autostart-beginning",
        "autostart-random"
      ],
      "default": "manual",
      "description": "The method by which the media player should start"
    },
    "mediaList": {
      "description": "A list of images or videos to configure the media player to operate on.",
      "type": "array",
      "items": {
        "oneOf": [
          {
            "title": "Image",
            "type": "object",
            "description": "Configuration for an image media.",
            "properties": {
              "imageUrl": {
                "type": "string",
                "description": "The url for the image to load."
              },
              "skipAfter": {
                "type": "number",
                "minimum": 5,
                "default": null,
                "description": "The number of seconds that should pass before skipping to the next media. (Minimum 5)."
              }
            },
            "required": [
              "imageUrl"
            ]
          },
          {
            "title": "Video",
            "type": "object",
            "description": "Configuration for a video media.",
            "properties": {
              "videoUrl": {
                "type": "string",
                "description": "The url of the video to load."
              },
              "skipAfter": {
                "type": "number",
                "minimum": 5,
                "default": null,
                "description": "The number of seconds that should pass before skipping to the next media. (Minimum 5)."
              },
              "volume": {
                "type": "number",
                "minimum": 0,
                "maximum": 1,
                "default": null,
                "description": "The volume to play the video at. (Minimum 0, maximum 1)"
              },
              "startTime": {
                "type": "number",
                "minimum": 0,
                "default": null,
                "description": "The time in seconds from the start of the video to begin playing the video at. (Minimum of 0)"
              },
              "rolloffStartDistance": {
                "type": "number",
                "minimum": 0,
                "default": null,
                "description": "The distance in meters away from the media player that the volume will begin to fall off. (Minimum 0)"
              },
              "endOfVideoAction": {
                "type": "string",
                "enum": [
                  "stop",
                  "loop",
                  "play-next"
                ],
                "default": null,
                "description": "The type of action to take at the end of the video."
              }
            },
            "required": [
              "videoUrl"
            ]
          }
        ]
      }
    }
  }
}
```

> [!NOTE]
> <span data-ttu-id="7cec7-206">Последние обновления с помощью мультимедийной консоли v 0.5.0</span><span class="sxs-lookup"><span data-stu-id="7cec7-206">Up to date with Multimedia Console v0.5.0</span></span>