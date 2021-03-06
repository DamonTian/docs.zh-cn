---
title: "如何：使用对象初始值设定项初始化对象（C# 编程指南）"
ms.date: 07/20/2015
ms.prod: .net
ms.technology: devlang-csharp
ms.topic: article
helpviewer_keywords:
- object initializers [C#], how to use
- objects [C#], initializing
ms.assetid: 4b75ebb2-2e29-43de-929c-d736a8f27ce6
caps.latest.revision: "20"
author: BillWagner
ms.author: wiwagn
ms.openlocfilehash: d1e65f8519062f6bceeb466a3b72c5719c0918f7
ms.sourcegitcommit: 4f3fef493080a43e70e951223894768d36ce430a
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/21/2017
---
# <a name="how-to-initialize-objects-by-using-an-object-initializer-c-programming-guide"></a>如何：使用对象初始值设定项初始化对象（C# 编程指南）
可以使用对象初始值设定项以声明方式初始化类型对象，而无需显式调用类型的构造函数。  
  
 以下示例演示如何将对象初始值设定项用于命名对象。 编译器通过首先访问默认实例构造函数，然后处理成员初始化来处理对象初始值设定项。 因此，如果默认构造函数在类中声明为 `private`，则需要公共访问的对象初始值设定项将失败。  
  
 如果要定义匿名类型，则必须使用对象初始值设定项。 有关详细信息，请参阅[如何：在查询中返回元素属性的子集](../../../csharp/programming-guide/classes-and-structs/how-to-return-subsets-of-element-properties-in-a-query.md)。  
  
## <a name="example"></a>示例  
 下面的示例演示如何使用对象初始值设定项初始化新的 `StudentName` 类型。  
  
 [!code-csharp[csProgGuideLINQ#35](../../../csharp/programming-guide/arrays/codesnippet/CSharp/how-to-initialize-objects-by-using-an-object-initializer_1.cs)]  
  
## <a name="example"></a>示例  
 下面的示例演示如何使用集合初始值设定项来初始化 `StudentName` 类型的集合。 请注意，集合初始值设定项是一系列由逗号分隔的对象初始值设定项。  
  
 [!code-csharp[csProgGuideLINQ#36](../../../csharp/programming-guide/arrays/codesnippet/CSharp/how-to-initialize-objects-by-using-an-object-initializer_2.cs)]  
  
## <a name="compiling-the-code"></a>编译代码  
 若要运行此代码，请将该类复制并粘贴到已经在 [!INCLUDE[vsprvs](~/includes/vsprvs-md.md)] 中创建的 Visual C# 控制台应用程序项目中。  
  
## <a name="see-also"></a>另请参阅  
 [C# 编程指南](../../../csharp/programming-guide/index.md)  
 [对象和集合初始值设定项](../../../csharp/programming-guide/classes-and-structs/object-and-collection-initializers.md)
