---
ms.openlocfilehash: ba9c00a9dfa055c518eb60bca3acc59a3cc89381
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: "145114875"
---
Рабочий процесс — это настраиваемый автоматизированный процесс, который будет выполнять одно или несколько заданий. Рабочие процессы определяются файлом YAML, возвращенным в репозиторий, и будут выполняться при активации события в репозитории. Либо их можно активировать вручную или по определенному расписанию.

Рабочие процессы определяются в каталоге `.github/workflows` в репозитории, а репозиторий может иметь несколько рабочих процессов, каждый из которых может выполнять разные наборы задач. Например, у вас может быть один рабочий процесс для создания и тестирования запросов на вытягивание, другой рабочий процесс — для развертывания приложения при каждом создании выпуска, а также еще один рабочий процесс, добавляющий метку каждый раз, когда кто-то открывает новую проблему.