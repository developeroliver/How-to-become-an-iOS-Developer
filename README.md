# Comment devenir un développeur iOS
L'objectif de ce document est la création d'un référentiel contenant des informations sur la façon de commencer et de progresser dans ma carrière en devenant un développeur iOS expert. Ce document pourrait également servir de guide d'entretien pour couvrir les sujets les plus importants.

# Comment commencer ?
Si vous n'êtes pas nouveau dans le monde de la programmation, mais que vous êtes pour iOS, suivez ce qui suit [quick guide](https://github.com/pitt500/how-to-become-an-ios-developer/blob/master/QuickGuide.md) d'abord. Si vous avez déjà de l'expérience avec iOS et que vous voulez dominer tous les sujets pour devenir un expert, veuillez continuer à lire le document.

# Deux façons
Divisons la feuille de route en deux grands thèmes :
* [Computer Science](#computer-science).

Ce sujet est souvent ignoré par certains développeurs qui pensent que les développeurs mobiles "n'ont pas besoin" de construire des algorithmes complexes. Il s'agit d'une hypothèse erronée. Si vous voulez devenir le meilleur développeur (peu importe le langage ou la plateforme), vous devez étudier les algorithmes et connaître les structures de données les plus utilisées.

* [iOS](#ios).

Le monde de l'iOS est vaste. Il y a beaucoup de sujets à apprendre depuis Cocoa/Cocoa Touch, les design patterns, les architectures logicielles et bien sûr, les langages Swift et Objective-C. Ce guide vous aidera à vous concentrer et à trouver un moyen d'étudier tous ces concepts.

# Informatique
La liste suivante présente les concepts de base à apprendre et à mettre en forme dans le domaine de l'informatique :
* [Algorithms](#algorithms)
* [Data Structures](#data-structures)

### Références pour l'étude :
* [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club)
* [Cracking the coding interview](http://www.crackingthecodinginterview.com/)
* [CLRS](https://www.amazon.com.mx/gp/product/0262033844/ref=ox_sc_saved_title_6?smid=AVDBXBAVVSXLQ&psc=1)

## Algorithmes
* [Big-O Notation](https://www.youtube.com/watch?v=D6xkbGLQesk)
* [Bit Manipulation](https://docs.swift.org/swift-book/LanguageGuide/AdvancedOperators.html)
* [Sorting](https://github.com/raywenderlich/swift-algorithm-club#sorting)
* [Recursion](https://www.youtube.com/watch?v=B0NtAFf4bvU)
* [Dynamic Programming](https://www.byte-by-byte.com/dpbook/)

> Vérifier [Cracking the coding interview](http://www.crackingthecodinginterview.com/) pour plus de détails

## Data Structures
* [Arrays](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Strings](https://docs.swift.org/swift-book/LanguageGuide/StringsAndCharacters.html)
* [Sets](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Dictionaries](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Lists](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Linked%20List)
* [Stacks](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Stack)
* [Queues](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Queue)
* [Trees](https://github.com/raywenderlich/swift-algorithm-club#trees)
* [Graphs](https://github.com/raywenderlich/swift-algorithm-club#graphs)

> Vérifier [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club) pour plus de details


# iOS
La liste suivante comprend les concepts les plus importants que vous devez connaître pour développer des applications pour iOS :
* [Languages](#languages)
* [Memory Management](#memory-management)
* [Multithreading](#multithreading)
* [Testing](#testing)
* [App Distribution](#app-distribution)
* [Design Patterns](#design-patterns)
* [Human Interface Guidelines](#human-interface-guidelines)
* [Cocoa Touch](#cocoa-touch)
* [Networking](#networking)
* [Push Notifications](#push-notifications)
* [Persisting Data](#persisting-data)
* [SwiftUI](#swiftui)
* [Internationalization](#internationalization)
* [Reactive Funtional Programming](#reactive-functional-programming)
* [Architecture](#architecture)
* [Debugging](#Debugging)

# Langages
iOS supporte deux langages : Objective-C (utilisé depuis deux décennies) et Swift depuis 2014. Vous pouvez créer des applications avec un seul de ces langages ou les mélanger si cela vous convient. Aujourd'hui, Apple a choisi Swift comme langage principal pour le développement, cependant, il y a beaucoup d'applications anciennes qui nécessitent encore le support de l'Objective-C (parce qu'il est coûteux et long de faire une migration), c'est pourquoi il est important de connaître les deux langages.

## Quelle langue apprendre ?
Si vous êtes nouveau et que vous vous demandez par où commencer, je vous recommande de commencer par Swift, parce qu'il est bien robuste et supporté aujourd'hui, de le garder comme langage principal pour développer des applications iOS, mais aussi de garder des connaissances en Objective-C, qui vous aideront lors d'entretiens ou dans des situations où vous aurez besoin d'interagir avec ce langage.

## Swift
* [Official website](https://swift.org/)
* [Language guide](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
* [Design guidelines](https://swift.org/documentation/api-design-guidelines/)
* [Swift style guide](https://google.github.io/swift/) (by Google)
* [Swift style guide](https://github.com/raywenderlich/swift-style-guide) (by RayWenderlich)

## Objective-C
* [Official Objective-C documentation](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [Blocks](https://www.youtube.com/watch?v=FS4JAy1Wy3w)
* [KVO](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html)
* [KVC](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/KeyValueCoding/index.html)
* [Bridging with Swift](https://developer.apple.com/documentation/swift/imported_c_and_objective-c_apis/importing_objective-c_into_swift#:~:text=Xcode%20offers%20to%20create%20this,by%20%22%2DBridging%2DHeader.)

# Memory Management
* [Automatic Reference Counting](https://docs.swift.org/swift-book/LanguageGuide/AutomaticReferenceCounting.html)
* [Memory Safety](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html)
* [Value vs Reference Types](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html)
* [Understanding Swift Performance](https://developer.apple.com/videos/play/wwdc2016/416/)
* [Improving Battery Life and Performance](https://developer.apple.com/videos/play/wwdc2019/417/)
* [iOS Memory Deep Dive](https://developer.apple.com/videos/play/wwdc2018/416/)

# Multithreading
* [Grand Central Dispatch Tutorial](https://www.raywenderlich.com/5370-grand-central-dispatch-tutorial-for-swift-4-part-1-2)
* [Operations Tutorial](https://www.raywenderlich.com/5293-operation-and-operationqueue-tutorial-in-swift)
* [Concurrency By Tutorials](https://store.raywenderlich.com/products/concurrency-by-tutorials)
* [Concurrent Programming with GCD](https://developer.apple.com/videos/play/wwdc2016/720/)
* [Modernizing Grand Central Dispatch Usage](https://developer.apple.com/videos/play/wwdc2017/706/)
* [Apple Documentation for GCD](https://developer.apple.com/documentation/DISPATCH)
* [Apple Documentation for Operations](https://developer.apple.com/documentation/foundation/operation)

# Testing
* [XCTest Framework](https://developer.apple.com/documentation/xctest)
* [Unit and UI Testing in iOS](https://www.raywenderlich.com/960290-ios-unit-testing-and-ui-testing-tutorial)
* [Testing in Xcode](https://developer.apple.com/videos/play/wwdc2019/413/)
* [UI Testing in Xcode](https://developer.apple.com/videos/play/wwdc2015/406/)
* [Getting Started with UI Testing](https://www.swiftbysundell.com/articles/getting-started-with-xcode-ui-testing-in-swift/)
* [Integration tests](https://www.swiftbysundell.com/articles/integration-tests-in-swift/)
* [Test Driven Developments in iOS](https://store.raywenderlich.com/products/ios-test-driven-development)

## Beta Distribution
* [TestFlight](https://developer.apple.com/videos/play/app-store-connect/101/)

# App Distribution
* [App Store Connect](https://developer.apple.com/videos/play/wwdc2019/301/)
* [App Distribution from Ad-hoc to Enterprise](https://developer.apple.com/videos/play/wwdc2019/304/)

# Design Patterns
Les patrons de conception sont des modèles qui répondent à des problèmes bien connus et qui nous aident à créer des applications de grande qualité, faciles à entretenir et évolutives. Les ressources suivantes vous aideront à en savoir plus sur les modèles utilisés dans iOS.

* [Design Patterns in Swift](https://refactoring.guru/design-patterns/swift)
* [Design Patterns by Tutorials](https://store.raywenderlich.com/products/design-patterns-by-tutorials)
* [Advanced iOS Architecture](https://store.raywenderlich.com/products/advanced-ios-app-architecture)
* [SOLID principles applied to Swift](https://marcosantadev.com/solid-principles-applied-swift/)
* [Clean Architecture](https://www.amazon.com/-/es/Clean-Architecture-Craftsmans-Software-Structure-ebook-dp-B075LRM681/dp/B075LRM681/ref=mt_kindle?_encoding=UTF8&me=&qid=1591475974)
* [Protocol-Oriented Programming](https://developer.apple.com/videos/play/wwdc2015/408/)

# Human Interface Guidelines
Apple nous fournit quelques principes de conception pour toutes les différentes plateformes de son écosystème comme macOS, WatchOS, tvOS et bien sûr iOS (iPadOS inclus). Apprenez ce sujet afin de fournir une meilleure expérience utilisateur à vos utilisateurs dans toutes vos apps. C'est ce qui fait la différence entre "une autre application aléatoire" et "l'application que tout le monde veut et sait utiliser".

* [Human Interface Guidelines for iOS](https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/)

# Cocoa Touch
* [UIKit](https://developer.apple.com/documentation/uikit)
* [Foundation](https://developer.apple.com/documentation/foundation)

## Auto layout
* [Auto Layout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html)
* [Auto Layout tutorial](https://www.raywenderlich.com/811496-auto-layout-tutorial-in-ios-getting-started)
* [Auto Layout by tutorials](https://store.raywenderlich.com/products/auto-layout-by-tutorials)

# Networking
* [URLSession](https://developer.apple.com/documentation/foundation/urlsession)
* [URLSession Tutorial](https://www.raywenderlich.com/3244963-urlsession-tutorial-getting-started)
* [URLSession Best Practices](https://developer.apple.com/videos/play/wwdc2016/711/)

# Push Notifications
* [Push Notifications by tutorials](https://store.raywenderlich.com/products/push-notifications-by-tutorials)

# Persisting Data
* [Saving Data in iOS](https://www.raywenderlich.com/5429634-saving-data-in-ios)
* [UserDefaults](https://developer.apple.com/documentation/foundation/userdefaults)
* [Saving data with UserDefaults](https://www.hackingwithswift.com/example-code/system/how-to-save-user-settings-using-userdefaults)
* [Property Lists](https://www.youtube.com/watch?v=2Fed9NbSXqw)
* [Encoding and Decoding objects](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types)

## Core Data
* [Core Data](https://developer.apple.com/documentation/coredata)
* [Core Data by Big Mountain](https://www.bigmountainstudio.com/core-data)
* [Beginning Core Data](https://www.raywenderlich.com/7104-beginning-core-data)
* [Intermadiate Core Data](https://www.raywenderlich.com/3815-intermediate-core-data)
* [Multiple Contexts in Core Data](https://www.raywenderlich.com/7586-multiple-managed-object-contexts-with-core-data-tutorial)
* [Core Data by tutorials](https://store.raywenderlich.com/products/core-data-by-tutorials)
* [Core Data for SwiftUI](https://www.raywenderlich.com/9335365-core-data-with-swiftui-tutorial-getting-started)

## External libraries
* [Realm](https://realm.io/docs/swift/latest)
* [SQLite](https://www.raywenderlich.com/6620276-sqlite-with-swift-tutorial-getting-started)

# SwiftUI
* [Official Apple SwiftUI Tutorials](https://developer.apple.com/tutorials/swiftui/)
* [Thinking of SwiftUI](https://www.objc.io/books/thinking-in-swiftui/)
* [Hacking with iOS: SwiftUI Edition](https://www.hackingwithswift.com/books/ios-swiftui)
* [SwiftUI Essentials](https://developer.apple.com/videos/play/wwdc2019/216/)
* [SwiftUI on all Devices](https://developer.apple.com/videos/play/wwdc2019/240/)

## Xcode Previews
* [Mastering Xcode Previews](https://developer.apple.com/videos/play/wwdc2019/233/)

# Internationalization
* [Localize an App](https://developer.apple.com/documentation/xcode/localizing_your_app)
* [Localized Experience in iOS 13](https://developer.apple.com/videos/play/wwdc2019/403/)


# Reactive Functional Programming

## Combine
* [Combine Documentation from Apple](https://developer.apple.com/documentation/combine)
* [Combine: Asynchronous Programming with Swift](https://www.raywenderlich.com/books/combine-asynchronous-programming-with-swift/v2.0)

## RxSwift
* [Official Repo](https://github.com/ReactiveX/RxSwift)
* [RxSwift: Reactive Programming with Swift](https://www.raywenderlich.com/books/rxswift-reactive-programming-with-swift/v4.0)

# Architecture
* [Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture)

# Debugging

## Instruments
* [Getting Started with Instruments](https://developer.apple.com/videos/play/wwdc2019/411/)
