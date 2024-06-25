# ToDo_List_App

---

### 프로젝트 개요

ToDo List 앱은 SwiftUI와 Core Data를 사용하여 할 일을 관리할 수 있는 간단한 iOS 앱입니다. 이 프로젝트를 통해 iOS 개발의 기본기를 익히고, SwiftUI를 활용한 사용자 인터페이스 설계, Core Data를 이용한 데이터 저장 및 관리, 그리고 UserNotifications 프레임워크를 통한 알림 기능을 구현하는 방법을 연습할 수 있었습니다.

### 프로젝트 후기

이 프로젝트를 통해 SwiftUI를 사용하여 사용자 인터페이스를 설계하고, Core Data를 통해 데이터를 저장하고 관리하는 방법을 익혔습니다. 또한, UserNotifications 프레임워크를 사용하여 로컬 알림을 설정하는 방법을 학습했습니다. 이 모든 기능을 통합하여 실용적인 iOS 앱을 개발하는 경험을 쌓을 수 있었습니다.

이 프로젝트는 iOS 개발의 기본기를 익히고, 실제 애플리케이션에서 필요한 다양한 기술을 연습하는 데 큰 도움이 되었습니다. 이를 통해 iOS 개발에 대한 이해도를 높이고, 더 복잡한 프로젝트를 진행할 수 있는 자신감을 얻게 되었습니다.

---

### **기능 설명**

- **할 일 추가**
    - 사용자는 새로운 할 일을 추가할 수 있습니다.
    - 할 일을 추가할 때 제목과 마감일을 설정할 수 있습니다.
    - 추가된 할 일은 Core Data에 저장되어 앱을 재실행해도 유지됩니다.
- **할 일 삭제**
    - 사용자는 리스트에서 할 일을 삭제할 수 있습니다.
    - 삭제된 할 일은 Core Data에서 제거되어 더 이상 리스트에 나타나지 않습니다.
- **할 일 편집**
    - 사용자는 기존 할 일의 제목과 마감일을 수정할 수 있습니다.
    - 수정된 내용은 Core Data에 업데이트되어 저장됩니다.
- **할 일 완료 표시**
    - 사용자는 할 일을 완료하면 체크 표시를 할 수 있습니다.
    - 완료된 할 일은 체크 아이콘이 변경되며, 상태가 저장됩니다.
- **알림 설정**
    - 마감일에 가까워지면 알림을 받을 수 있도록 설정할 수 있습니다.
    - 사용자가 설정한 마감일에 맞춰 알림이 표시됩니다.

---

### 기술 스택

- **Swift**: 애플의 프로그래밍 언어로, iOS 앱 개발에 사용됩니다.
- **SwiftUI**: 애플의 UI 프레임워크로, 선언적인 방법으로 사용자 인터페이스를 구축할 수 있습니다.
- **Core Data**: 애플의 데이터 관리 프레임워크로, 데이터를 저장하고 관리하는 데 사용됩니다.
- **UserNotifications**: 애플의 알림 프레임워크로, 로컬 알림을 설정하고 관리하는 데 사용됩니다.

---

### 구현 과정

- **AppDelegate 설정**
    - 앱이 실행될 때 사용자에게 알림 권한을 요청합니다.
    - 앱이 실행 중일 때 알림이 표시되도록 델리게이트 메서드를 구현합니다.
- **할 일 추가 기능**
    - 사용자가 제목과 마감일을 입력하여 새로운 할 일을 추가할 수 있습니다.
    - 할 일이 추가될 때, Core Data에 저장되고, 알림이 설정됩니다.
- **할 일 편집 기능**
    - 사용자가 기존 할 일을 선택하여 제목과 마감일을 수정할 수 있습니다.
    - 수정된 내용은 Core Data에 저장됩니다.
- **할 일 완료 표시 기능**
    - 사용자가 할 일을 완료하면 체크 표시를 할 수 있습니다.
    - 완료 상태는 Core Data에 저장되며, 체크 아이콘이 변경됩니다.
- **할 일 삭제 기능**
    - 사용자가 리스트에서 할 일을 삭제할 수 있습니다.
    - 삭제된 할 일은 Core Data에서 제거됩니다.

---

### 스크린샷

1. 메인 화면
    
    ![스크린샷 2024-06-03 오후 7.08.09.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f9f35de7-0091-4a79-819a-501ef9435828/51379cec-7450-4d55-91ec-9975be26f240/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-06-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_7.08.09.png)
    
2. 할 일 추가 화면
    
    ![스크린샷 2024-06-03 오후 7.07.43.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f9f35de7-0091-4a79-819a-501ef9435828/e1286827-e6f7-4fe6-8f22-f4d8b95e6fb3/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-06-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_7.07.43.png)
    
3. 할 일 편집 화면
    
    ![스크린샷 2024-06-03 오후 7.08.01.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f9f35de7-0091-4a79-819a-501ef9435828/c6e1b898-9a6b-4e69-8516-e0eb6437208f/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-06-03_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_7.08.01.png)
    

---

### 주요 코드 스니펫 및 상세 설명

1. AppDelegate.swift

```swift
import UIKit
import UserNotifications

class AppDelegate: NSObject, UIApplicationDelegate, UNUserNotificationCenterDelegate {
    func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool {
        UNUserNotificationCenter.current().requestAuthorization(options: [.alert, .badge, .sound]) { granted, error in
            if let error = error {
                print("Error requesting notification authorization: \(error)")
            }
        }
        UNUserNotificationCenter.current().delegate = self
        return true
    }
    
    // 알림을 앱이 활성화되어 있을 때 처리하는 메서드 추가
    func userNotificationCenter(_ center: UNUserNotificationCenter, willPresent notification: UNNotification, withCompletionHandler completionHandler: @escaping (UNNotificationPresentationOptions) -> Void) {
        completionHandler([.banner, .sound])
    }
}
```

1. AddTaskView.swift

```swift
import SwiftUI
import UserNotifications

struct AddTaskView: View {
    @Environment(\.managedObjectContext) private var viewContext
    @Environment(\.presentationMode) var presentationMode
    
    @State private var title: String = ""
    @State private var dueDate: Date = Date()
    
    var body: some View {
        NavigationView {
            Form {
                TextField("Title", text: $title)
                DatePicker("Due Date", selection: $dueDate, displayedComponents: .date)
                Button(action: addTask) {
                    Text("Add Task")
                }
            }
            .navigationTitle("New Task")
            .navigationBarItems(leading: Button(action: {
                presentationMode.wrappedValue.dismiss()
            }) {
                Text("Cancel")
            })
        }
    }
    
    private func addTask() {
        let newTask = Task(context: viewContext)
        newTask.title = title
        newTask.dueDate = dueDate
        newTask.isCompleted = false
        
        scheduleNotification(for: newTask)
        saveContext()
        presentationMode.wrappedValue.dismiss()
    }
    
    private func scheduleNotification(for task: Task) {
        let content = UNMutableNotificationContent()
        content.title = "ToDo Reminder"
        content.body = task.title ?? "No Title"
        content.sound = .default
        
        let triggerDate = Calendar.current.dateComponents([.year, .month, .day, .hour, .minute], from: task.dueDate ?? Date())
        let trigger = UNCalendarNotificationTrigger(dateMatching: triggerDate, repeats: false)
        
        let request = UNNotificationRequest(identifier: UUID().uuidString, content: content, trigger: trigger)
        UNUserNotificationCenter.current().add(request)
    }
    
    private func saveContext() {
        do {
            try viewContext.save()
        } catch {
            let nsError = error as NSError
            fatalError("Unresolved error \(nsError), \(nsError.userInfo)")
        }
    }
}
```

1. EditTaskView.swift

```swift
import SwiftUI

struct EditTaskView: View {
    @Environment(\.managedObjectContext) private var viewContext
    @Environment(\.presentationMode) var presentationMode

    @ObservedObject var task: Task

    @State private var title: String = ""
    @State private var dueDate: Date = Date()

    var body: some View {
        NavigationView {
            Form {
                TextField("Title", text: $title)
                DatePicker("Due Date", selection: $dueDate, displayedComponents: .date)
                Button(action: saveTask) {
                    Text("Save Changes")
                }
            }
            .navigationTitle("Edit Task")
            .navigationBarItems(leading: Button(action: {
                presentationMode.wrappedValue.dismiss()
            }) {
                Text("Cancel")
            })
        }
        .onAppear {
            title = task.title ?? ""
            dueDate = task.dueDate ?? Date()
        }
    }

    private func saveTask() {
        task.title = title
        task.dueDate = dueDate
        saveContext()
        presentationMode.wrappedValue.dismiss()
    }

    private func saveContext() {
        do {
            try viewContext.save()
        } catch {
            let nsError = error as NSError
            fatalError("Unresolved error \(nsError), \(nsError.userInfo)")
        }
    }
}
```

1. ContentView.swift

```swift
import SwiftUI
import CoreData

struct ContentView: View {
    @Environment(\.managedObjectContext) private var viewContext
    @FetchRequest(
        entity: Task.entity(),
        sortDescriptors: [NSSortDescriptor(keyPath: \Task.dueDate, ascending: true)],
        animation: .default)
    private var tasks: FetchedResults<Task>

    @State private var showingAddTaskView = false

    var body: some View {
        NavigationView {
            List {
                ForEach(tasks) { task in
                    NavigationLink(destination: EditTaskView(task: task).environment(\.managedObjectContext, viewContext)) {
                        TaskRowView(task: task)
                    }
                }
                .onDelete(perform: deleteTasks)
            }
            .navigationTitle("To-Do List")
            .navigationBarItems(trailing: Button(action: {
                showingAddTaskView.toggle()
            }) {
                Image(systemName: "plus")
            })
            .sheet(isPresented: $showingAddTaskView) {
                AddTaskView().environment(\.managedObjectContext, viewContext)
            }
        }
    }

    private func deleteTasks(offsets: IndexSet) {
        offsets.map { tasks[$0] }.forEach(viewContext.delete)
        saveContext()
    }

    private func saveContext() {
        do {
            try viewContext.save()
        } catch {
            let nsError = error as NSError
            fatalError("Unresolved error \(nsError), \(nsError.userInfo)")
        }
    }
}
```

1. TaskRowView.swift

```swift
import SwiftUI

struct TaskRowView: View {
    @ObservedObject var task: Task

    var body: some View {
        HStack {
            Text(task.title ?? "Untitled")
                .font(.headline)
                .foregroundColor(task.isCompleted ? .gray : .black)
            Spacer()
            Text(task.dueDate ?? Date(), style: .date)
                .font(.subheadline)
                .foregroundColor(.secondary)
            Button(action: {
                toggleCompletion()
            }) {
                Image(systemName: task.isCompleted ? "checkmark.circle.fill" : "circle")
                    .foregroundColor(task.isCompleted ? .green : .red)
            }
            .buttonStyle(BorderlessButtonStyle()) // Button 내부에 Button 추가 시 필요
            Button(action: {
                toggleCompletion()
            }) {
                Text("완료")
                    .foregroundColor(.blue)
            }
        }
        .padding()
        .background(RoundedRectangle(cornerRadius: 10).fill(Color(.systemGray6)))
        .overlay(
            RoundedRectangle(cornerRadius: 10)
                .stroke(Color(.systemGray4), lineWidth: 1)
        )
    }

    private func toggleCompletion() {
        task.isCompleted.toggle()
        saveContext()
    }

    private func saveContext() {
        do {
            try task.managedObjectContext?.save()
        } catch {
            let nsError = error as NSError
            fatalError("Unresolved error \(nsError), \(nsError.userInfo)")
        }
    }
}
```
