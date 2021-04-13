---
title: Использование порождаемого Интерактаблес
description: Узнайте, как создать, использовать и настроить порожденный интерактаблес для размещения элементов в Алтспацеврных пространствах.
ms.date: 02/10/2021
ms.topic: article
keywords: порожденный, взаимодействия, настройки
ms.openlocfilehash: 7f4b87591b2e11b2084af4d2bf83748ed51fd193
ms.sourcegitcommit: d84a6adf631ff02b106e682238f2861477caef1e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/08/2021
ms.locfileid: "107213924"
---
# <a name="using-the-interactables-spawner"></a><span data-ttu-id="83192-104">Использование порождаемого Интерактаблес</span><span class="sxs-lookup"><span data-stu-id="83192-104">Using the Interactables Spawner</span></span>

<span data-ttu-id="83192-105">Порожденный Интерактаблес позволяет размещать взаимодействующие элементы в своем событии, в мире или в основном пространстве.</span><span class="sxs-lookup"><span data-stu-id="83192-105">The Interactables Spawner allows you to place interactable items in your event, world, or home-space.</span></span> <span data-ttu-id="83192-106">Эта функция в настоящее время является частью нашей [программы раннего доступа](../world-building/early-access.md) и будет недоступна, если вы не выбрали свое основное меню.</span><span class="sxs-lookup"><span data-stu-id="83192-106">This feature is currently part of our [Early Access Program](../world-building/early-access.md) and won't be available unless you've opted in through your Main Menu.</span></span>

> [!NOTE]
> <span data-ttu-id="83192-107">Хотя мы продолжаем пилотное развертывание этой функции, имейте в виду, что порождение слишком большого количества интерактаблес может повлиять на производительность среды или события.</span><span class="sxs-lookup"><span data-stu-id="83192-107">While we continue to pilot this feature please be aware that spawning too many interactables may affect the performance of your environment or event.</span></span> 

## <a name="creating-an-interactable"></a><span data-ttu-id="83192-108">Создание взаимодействующего</span><span class="sxs-lookup"><span data-stu-id="83192-108">Creating an interactable</span></span>

<span data-ttu-id="83192-109">Чтобы превратить объект в взаимодействующий объект, выполните следующие действия.</span><span class="sxs-lookup"><span data-stu-id="83192-109">To turn your object into an interactable object:</span></span>

1. <span data-ttu-id="83192-110">Поместите объект в свое пространство.</span><span class="sxs-lookup"><span data-stu-id="83192-110">Place the object in your space.</span></span>
2. <span data-ttu-id="83192-111">Затем найдите запись в списке объектов и щелкните **значок шестеренки** рядом с ним, чтобы открыть его параметры:</span><span class="sxs-lookup"><span data-stu-id="83192-111">Then, find the entry in the object list, and select the **gear icon** next to it to open its settings:</span></span>

![Открытие редактора мира с выделенным списком объектов](images/interactables-spawner-img-01.png)

<span data-ttu-id="83192-113">На странице Параметры можно найти новый флажок **"порожденный объект"**, который будет использоваться для взаимодействия с объектом.</span><span class="sxs-lookup"><span data-stu-id="83192-113">On the settings page you’ll find a new checkbox **“Object spawner“**, which is used to make it an interactable object.</span></span>

1. <span data-ttu-id="83192-114">Установите флажок и нажмите кнопку **подтвердить**.</span><span class="sxs-lookup"><span data-stu-id="83192-114">Check the box and select **confirm**.</span></span>
2. <span data-ttu-id="83192-115">В режиме редактирования можно перемещаться по месту порождения объекта в пространстве.</span><span class="sxs-lookup"><span data-stu-id="83192-115">While in edit mode, you can move around the object’s spawn location in the space.</span></span>
3. <span data-ttu-id="83192-116">Чтобы включить взаимодействие элементов, **закройте режим редактирования** .</span><span class="sxs-lookup"><span data-stu-id="83192-116">**Exit edit mode** to enable item interaction.</span></span>

![Окно обновления артефакта открыто в приложении Алтспацевр](images/interactables-spawner-img-02.png)

## <a name="other-customizations"></a><span data-ttu-id="83192-118">Другие настройки</span><span class="sxs-lookup"><span data-stu-id="83192-118">Other customizations</span></span>

<span data-ttu-id="83192-119">После включения **порождаемого объекта** при возврате к свойствам этого объекта будет доступен дополнительный параметр, который можно применить к порожденному объекту.</span><span class="sxs-lookup"><span data-stu-id="83192-119">After enabling **“Object spawner”** when you go back into the properties for that object, there will be an extra setting you can apply to how the spawned object behaves.</span></span>

> [!NOTE]
> <span data-ttu-id="83192-120">Масштабируемость объектного объекта. Этот параметр задает масштаб объекта при его выборе, по сравнению с "масштабом", который представляет собой масштаб отображения объекта в мире, прежде чем выбирать его в первый раз.</span><span class="sxs-lookup"><span data-stu-id="83192-120">Interactable object scale: This sets the scale of the object when it gets picked up, compared to “Scale” which is the scale of how the object appears in the world prior to picking it up for the first time.</span></span>

<span data-ttu-id="83192-121">Создатели комплектов могут заметить, что изменения в вашем пакете во время работы Алтспацевр вступят в силу только после перезапуска Алтспацевр.</span><span class="sxs-lookup"><span data-stu-id="83192-121">Kit makers may notice that changes to your Kit while AltspaceVR is running won't take effect until you restart AltspaceVR.</span></span>

<span data-ttu-id="83192-122">Недавно мы добавили кнопку на вкладку **умеренные параметры** , называемые **Перезагрузка наборов миров**.</span><span class="sxs-lookup"><span data-stu-id="83192-122">Recently we’ve added a button under the **Moderate Settings** tab called **Reload Worlds Kits**.</span></span> <span data-ttu-id="83192-123">Нажатие этой кнопки приводит к повторному вводу пространства, повторная загрузка всех наборов, в ходе которой будут скачиваться только новые версии пакетов, которые были обновлены в Алтспацевр.</span><span class="sxs-lookup"><span data-stu-id="83192-123">Clicking this button causes (just you) to reenter the space, reloading all Kits again, which will download only new versions of the Kits that have been updated while you were in AltspaceVR.</span></span>

![Средняя панель параметров открыта в приложении Алтспацевр](images/interactables-spawner-img-03.png)