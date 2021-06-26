---
title: Поиск версии приложения Алтспацевр
description: Узнайте, как использовать приложение, параметры и журналы клиента Алтспацевр для поиска версии Алтспацевр, которую вы используете в данный момент.
ms.date: 02/10/2021
ms.topic: article
keywords: версия приложения
ms.openlocfilehash: 6b710e1724b890fa7ba0eecfcd774ef63128d5b7
ms.sourcegitcommit: 2db596ab5a1ecd4901a8c893741cc4d06f6aecea
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/25/2021
ms.locfileid: "112923181"
---
# <a name="finding-the-altspacevr-app-version"></a><span data-ttu-id="bfa89-104">Поиск версии приложения Алтспацевр</span><span class="sxs-lookup"><span data-stu-id="bfa89-104">Finding the AltspaceVR app version</span></span>

<span data-ttu-id="bfa89-105">В ходе устранения проблемы может быть запрошена версия приложения Алтспацевр, которая сейчас выполняется.</span><span class="sxs-lookup"><span data-stu-id="bfa89-105">In the course of troubleshooting an issue, you may be asked what version of the AltspaceVR app you're currently running.</span></span>

## <a name="in-altspacevr"></a><span data-ttu-id="bfa89-106">В Алтспацевр</span><span class="sxs-lookup"><span data-stu-id="bfa89-106">In AltspaceVR</span></span>

<span data-ttu-id="bfa89-107">Чтобы найти версию приложения в Алтспацевр, перейдите в меню " **Параметры** " и выберите " **о программе** " на панели навигации слева.</span><span class="sxs-lookup"><span data-stu-id="bfa89-107">To find the app version in AltspaceVR, navigate to the **settings menu** and select **About** in the left navigation bar.</span></span> <span data-ttu-id="bfa89-108">Здесь указывается версия приложения, как показано на снимке экрана ниже.</span><span class="sxs-lookup"><span data-stu-id="bfa89-108">The 'App Version' is reported here, as shown in the screenshot below.</span></span>

![Меню "Параметры" Открыть с помощью панели About "Открыть"](images/app-version-img-01.png)

## <a name="in-windows-system-settings"></a><span data-ttu-id="bfa89-110">В параметрах системы Windows</span><span class="sxs-lookup"><span data-stu-id="bfa89-110">In Windows System Settings</span></span>

<span data-ttu-id="bfa89-111">Если вы установили Алтспацевр с помощью Microsoft Store, можно дополнительно найти версию приложения в параметрах системы Windows.</span><span class="sxs-lookup"><span data-stu-id="bfa89-111">If you installed AltspaceVR via the Microsoft Store, you can additionally find the app version in the Windows system settings.</span></span>  <span data-ttu-id="bfa89-112">Этот сценарий хорошо подходит при создании отчета о версии приложения, если вы не можете успешно войти в клиент.</span><span class="sxs-lookup"><span data-stu-id="bfa89-112">This scenario is a good fit when reporting the app version if you're unable to successfully log into the client.</span></span>

<span data-ttu-id="bfa89-113">Чтобы найти версию приложения в параметрах системы Windows, откройте **меню "Пуск**", введите " **приложения & компоненты**" и выберите результат.</span><span class="sxs-lookup"><span data-stu-id="bfa89-113">To find the app version in Windows system settings, open the **Start Menu**, type in **Apps & Features**, and select the result.</span></span> <span data-ttu-id="bfa89-114">Перейдите по адресу **алтспацевр** в списке приложений.</span><span class="sxs-lookup"><span data-stu-id="bfa89-114">Navigate to **AltspaceVR** in the list of apps.</span></span> <span data-ttu-id="bfa89-115">Щелкните левой кнопкой мыши Алтспацевр и выберите в появившемся меню пункт **Дополнительные параметры** .</span><span class="sxs-lookup"><span data-stu-id="bfa89-115">Left-click AltspaceVR and select **Advanced Options** from the menu that appears.</span></span>

![Меню "приложения и компоненты" открыто с выделенным дополнительным параметром](images/app-version-img-02.png)

<span data-ttu-id="bfa89-117">В **дополнительных параметрах** в заголовке **спецификации** **версия приложения** должна быть указана справа от метки **версии** .</span><span class="sxs-lookup"><span data-stu-id="bfa89-117">In the **Advanced Options**, under the **Specifications** header, the **App Version** should be listed to the right of the **Version** label.</span></span>

![Дополнительные параметры открыть с выделенной версией приложения](images/app-version-img-03.png)

## <a name="in-client-logs"></a><span data-ttu-id="bfa89-119">В журналах клиента</span><span class="sxs-lookup"><span data-stu-id="bfa89-119">In Client Logs</span></span>

<span data-ttu-id="bfa89-120">Алтспацевр сообщает версию приложения в файле журнала клиента как "версию Алтспаце" во время запуска приложения.</span><span class="sxs-lookup"><span data-stu-id="bfa89-120">AltspaceVR reports the app version in the client logs file as "Altspace Version" during application startup.</span></span> <span data-ttu-id="bfa89-121">Это может быть хорошим вариантом для получения версии приложения, если вы не можете войти на клиент, но предпринималась попытка запуска до сбоя.</span><span class="sxs-lookup"><span data-stu-id="bfa89-121">This would be a good option to get the app version if you can't successfully log into the client, but it did attempt to start before failing.</span></span>

## <a name="windows"></a><span data-ttu-id="bfa89-122">Windows</span><span class="sxs-lookup"><span data-stu-id="bfa89-122">Windows</span></span>

<span data-ttu-id="bfa89-123">В Windows файл журнала клиента можно найти с помощью проводника Windows по адресу:</span><span class="sxs-lookup"><span data-stu-id="bfa89-123">On Windows, the client logs file can be found via Windows Explorer at:</span></span>

```
%userprofile%\AppData\LocalLow\Microsoft\AltspaceVR\Player.log
%userprofile%\AppData\LocalLow\Microsoft\AltspaceVR\Player-prev.log
```

<span data-ttu-id="bfa89-124">Этот файл перезаписывается каждый раз при запуске Алтспацевр.</span><span class="sxs-lookup"><span data-stu-id="bfa89-124">This file is overwritten each time you launch AltspaceVR.</span></span> <span data-ttu-id="bfa89-125">"Проигрыватель. log" представляет последний сеанс, а "Плайер-прев. log" представляет предыдущий сеанс.</span><span class="sxs-lookup"><span data-stu-id="bfa89-125">'Player.log' represents your latest session, and 'Player-prev.log' represents the previous session.</span></span>

## <a name="via-powershell"></a><span data-ttu-id="bfa89-126">Использование PowerShell</span><span class="sxs-lookup"><span data-stu-id="bfa89-126">Via PowerShell</span></span>

<span data-ttu-id="bfa89-127">Опытные пользователи могут выполнять поиск этой строки в журналах клиента с помощью PowerShell следующим образом:</span><span class="sxs-lookup"><span data-stu-id="bfa89-127">Advanced users can search the client logs for this string via PowerShell as follows:</span></span>

<span data-ttu-id="bfa89-128">Входные данные:</span><span class="sxs-lookup"><span data-stu-id="bfa89-128">Input:</span></span>

```
gc $env:userprofile\appdata\locallow\altspacevr\altspacevr\Player.log | ? { $_ -match "Altspace Version" }
```

<span data-ttu-id="bfa89-129">Выходные данные:</span><span class="sxs-lookup"><span data-stu-id="bfa89-129">Output:</span></span>

<span data-ttu-id="bfa89-130">[2,047] Алтспацевр версия: 3.2.23. e66c2</span><span class="sxs-lookup"><span data-stu-id="bfa89-130">[2.047] AltspaceVR Version: 3.2.23.e66c2</span></span>