---
title: Предоставление ролей мира
description: Ознакомьтесь с системой ролей и возможностей и получите пошаговые инструкции по предоставлению пользователям ролей в Алтспацевр.
ms.date: 04/14/2021
ms.topic: article
keywords: Роли
ms.openlocfilehash: 3a1d0f138b29fe545f52d851ff00062f156a860e
ms.sourcegitcommit: 2db596ab5a1ecd4901a8c893741cc4d06f6aecea
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/25/2021
ms.locfileid: "112923202"
---
# <a name="granting-world-roles"></a><span data-ttu-id="d663b-104">Предоставление ролей мира</span><span class="sxs-lookup"><span data-stu-id="d663b-104">Granting world roles</span></span>

<span data-ttu-id="d663b-105">Алтспаце имеет систему ролей и возможностей.</span><span class="sxs-lookup"><span data-stu-id="d663b-105">Altspace has a Roles and Abilities system.</span></span> <span data-ttu-id="d663b-106">Каждый пользователь может иметь несколько ролей, и их роли могут отличаться в зависимости от того, где они находятся.</span><span class="sxs-lookup"><span data-stu-id="d663b-106">Each person can have multiple roles and their roles can be different depending on where they are.</span></span> <span data-ttu-id="d663b-107">Каждая роль, в свою очередь, предоставляет одну или несколько возможностей.</span><span class="sxs-lookup"><span data-stu-id="d663b-107">Each role, in turn, gives you one or more abilities.</span></span> <span data-ttu-id="d663b-108">Например, если вы находитесь в своем собственном событии, вы автоматически получаете роли **ведущего приложения** и **модератора** .</span><span class="sxs-lookup"><span data-stu-id="d663b-108">For example, when you're in your own event, you automatically receive the **host** and **moderator** roles.</span></span> <span data-ttu-id="d663b-109">С этими двумя ролями вы можете запускать унрули пользователей, находиться на промежуточном уровне и, возможно, выпустить конфетти.</span><span class="sxs-lookup"><span data-stu-id="d663b-109">With those two roles you can kick unruly users, be on stage, and maybe release the confetti.</span></span>

1. <span data-ttu-id="d663b-110">Измените мир и просмотрите правый столбец для **контекстных ролей** ([управление мировыми](managing-worlds.md)ролями).</span><span class="sxs-lookup"><span data-stu-id="d663b-110">Edit your World and look over to the right column for **Contextual Roles** ([How to manage Worlds](managing-worlds.md))</span></span>

![Изменение ролей в разделе "контекстные роли" в мировых условиях](images/granting-roles.png)

2. <span data-ttu-id="d663b-112">Щелкните **Добавить пользователя** в поле **Контекстные роли** , если вы хотите предоставить определенные роли конкретным пользователям только для этого мира.</span><span class="sxs-lookup"><span data-stu-id="d663b-112">Click **Add User** under the **Contextual Roles** field if you want to grant specific roles to specific users just for this World.</span></span> <span data-ttu-id="d663b-113">Например, если вы хотите предоставить мне   +  **Модератор** узла, добавьте приведенный выше пример и выберите **сохранить**.</span><span class="sxs-lookup"><span data-stu-id="d663b-113">For example, if you want to give me **host** + **moderator**, you would add the above and select **Save**.</span></span> <span data-ttu-id="d663b-114">Формат **имени пользователя**, имя пользователя не учитывает регистр, выберите роль в раскрывающемся меню **Терраформер**, нажмите кнопку Добавить пользователя несколько раз, чтобы добавить дополнительных пользователей, а затем нажмите кнопку **Обновить**.</span><span class="sxs-lookup"><span data-stu-id="d663b-114">The format is **username**, username is case-insensitive, choose the role from the dropdown menu **Terraformer**, click Add User multiple times to keeping adding more users and then click **Update**.</span></span>

* <span data-ttu-id="d663b-115">Чтобы изменения вступили в силу в Алтспаце, следует сбросить место на диске, чтобы все присоединиться ко всем, чтобы присоединиться к этому миру.</span><span class="sxs-lookup"><span data-stu-id="d663b-115">In order for the change to take effect in Altspace, you should Reset Space the world forcing everyone to rejoin or have each user with a new role rejoin the world.</span></span>

3. <span data-ttu-id="d663b-116">Измените поле **Контекстные роли по умолчанию** в разделе **в VR** , если вы хотите предоставить роль каждому из них, который присоединяется к вашему миру.</span><span class="sxs-lookup"><span data-stu-id="d663b-116">Edit the **Default Contextual Roles** field, under the **In VR** section, if you want to grant a role to every one that joins your World.</span></span> <span data-ttu-id="d663b-117">Например, если вы хотите позволить людям работать и использовать рупор, чтобы они могли слышать друг друга, в то же время, добавьте следующее:</span><span class="sxs-lookup"><span data-stu-id="d663b-117">For example, if you want to let people fly and use the megaphone so they can hear each other while far part, add the following:</span></span>

```
pilot,megaphone_only
```

<span data-ttu-id="d663b-118">После выбора **обновления** сбросьте пространство в мире.</span><span class="sxs-lookup"><span data-stu-id="d663b-118">After you select **Update**, Reset Space in the World.</span></span> <span data-ttu-id="d663b-119">Это повлияет только на этот мир.</span><span class="sxs-lookup"><span data-stu-id="d663b-119">This will only affect this World.</span></span> <span data-ttu-id="d663b-120">Если вы хотите предоставить роли всем вселенной, измените те же поля в Вселенной.</span><span class="sxs-lookup"><span data-stu-id="d663b-120">If you want to grant roles to an entire Universe, edit the same fields on the Universe.</span></span> <span data-ttu-id="d663b-121">То же самое касается событий, если вы хотите, чтобы каждый в своем событии имел эти роли, необходимо добавить его в **роли Контексуал по умолчанию** самого события.</span><span class="sxs-lookup"><span data-stu-id="d663b-121">The same goes for events, if you want everyone in your event to have these roles you'll need to add this to the **Default Contexual Roles** of the event itself.</span></span>

## <a name="roles"></a><span data-ttu-id="d663b-122">Роли</span><span class="sxs-lookup"><span data-stu-id="d663b-122">Roles</span></span>

* <span data-ttu-id="d663b-123">**Megaphone_only** возможность говорить с пользователями в ушки, где бы они ни находились в мире</span><span class="sxs-lookup"><span data-stu-id="d663b-123">**Megaphone_only** - ability to speak into users' ears wherever they are in the World</span></span>
* <span data-ttu-id="d663b-124">**Модератор** — возможности, такие как « **Начало** », для поддержки декорум</span><span class="sxs-lookup"><span data-stu-id="d663b-124">**Moderator** - abilities like **kick** to maintain decorum</span></span>
* <span data-ttu-id="d663b-125">**Пилотный** режим — возможность переключения режима полета и порождения средства 6DOF Flight</span><span class="sxs-lookup"><span data-stu-id="d663b-125">**Pilot** - ability to toggle fly mode and spawn the 6DOF flight tool</span></span>
* <span data-ttu-id="d663b-126">Возможности **узла** , например, могут быть на этапе, иметь рупор</span><span class="sxs-lookup"><span data-stu-id="d663b-126">**Host** - abilities like being able to be on stage, have megaphone</span></span>
* <span data-ttu-id="d663b-127">**Терраформер** — возможность использования редактора мира дополнительные сведения о ([роли в событиях, мировых, группах и в алтспацевр](../getting-started/roles.md))</span><span class="sxs-lookup"><span data-stu-id="d663b-127">**Terraformer** - ability to use the World Editor More information about ([Roles in events, worlds, groups, and in AltspaceVR](../getting-started/roles.md))</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="d663b-128">Устранение неполадок</span><span class="sxs-lookup"><span data-stu-id="d663b-128">Troubleshooting</span></span>

<span data-ttu-id="d663b-129">**Можно ли удалить роли?**</span><span class="sxs-lookup"><span data-stu-id="d663b-129">**Can I delete roles?**</span></span>
<span data-ttu-id="d663b-130">Да, изменить мир, щелкнуть **Удалить** ниже роли, которую вы хотите удалить, и нажать кнопку **Обновить** .</span><span class="sxs-lookup"><span data-stu-id="d663b-130">Yes, edit your world, click **Remove** below the role you'd like to delete and click **Update**</span></span>

<span data-ttu-id="d663b-131">**Копируются ли роли при импорте из другого мира?**</span><span class="sxs-lookup"><span data-stu-id="d663b-131">**Are roles copied when a World is importing from another?**</span></span>
<span data-ttu-id="d663b-132">Нет, роли не копируются</span><span class="sxs-lookup"><span data-stu-id="d663b-132">No, roles aren't copied</span></span>