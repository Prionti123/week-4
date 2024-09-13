# week-4
#include <iostream>
#include <vector>
#include <algorithm>

int maxProfit(const std::vector<int>& prices) {
    if (prices.empty()) return

2.to-do list application
#include <iostream>
#include <vector>
#include <algorithm>

// Structure to define a task
struct Task {
    std::string name;
    int priority;  // 1: High, 2: Medium, 3: Low
};

// Comparison function for sorting tasks by priority
bool compareTasks(const Task& a, const Task& b) {
    return a.priority < b.priority;
}

int main() {
    std::vector<Task> tasks;
    int choice;

    do {
        std::cout << "1. Add a task\n2. Display tasks\n3. Sort tasks by priority\n4. Exit\n";
        std::cin >> choice;

        if (choice == 1) {
            Task t;
            std::cout << "Enter task name: ";
            std::cin.ignore();
            std::getline(std::cin, t.name);
            std::cout << "Enter priority (1: High, 2: Medium, 3: Low): ";
            std::cin >> t.priority;
            tasks.push_back(t);
        } else if (choice == 2) {
            std::cout << "\nYour tasks:\n";
            for (const auto& task : tasks) {
                std::cout << "Task: " << task.name << ", Priority: " << task.priority << "\n";
            }
        } else if (choice == 3) {
            std::sort(tasks.begin(), tasks.end(), compareTasks);
            std::cout << "Tasks sorted by priority!\n";
        }

    } while (choice != 4);

    return 0;
}
3.Reverse the order of elements
#include <iostream>
#include <vector>
#include <algorithm>

// Structure to define a task
struct Task {
    std::string name;
    int priority;  // 1: High, 2: Medium, 3: Low
};

// Comparison function for sorting tasks by priority
bool compareTasks(const Task& a, const Task& b) {
    return a.priority < b.priority;
}

int main() {
    std::vector<Task> tasks;
    int choice;

    do {
        std::cout << "1. Add a task\n2. Display tasks\n3. Sort tasks by priority\n4. Exit\n";
        std::cin >> choice;

        if (choice == 1) {
            Task t;
            std::cout << "Enter task name: ";
            std::cin.ignore();
            std::getline(std::cin, t.name);
            std::cout << "Enter priority (1: High, 2: Medium, 3: Low): ";
            std::cin >> t.priority;
            tasks.push_back(t);
        } else if (choice == 2) {
            std::cout << "\nYour tasks:\n";
            for (const auto& task : tasks) {
                std::cout << "Task: " << task.name << ", Priority: " << task.priority << "\n";
            }
        } else if (choice == 3) {
            std::sort(tasks.begin(), tasks.end(), compareTasks);
            std::cout << "Tasks sorted by priority!\n";
        }

    } while (choice != 4);

    return 0;
}
4.recomendation c++
#include <iostream>
#include <vector>
#include <algorithm>

// Structure to define a task
struct Task {
    std::string name;
    int priority;  // 1: High, 2: Medium, 3: Low
};

// Comparison function for sorting tasks by priority
bool compareTasks(const Task& a, const Task& b) {
    return a.priority < b.priority;
}

int main() {
    std::vector<Task> tasks;
    int choice;

    do {
        std::cout << "1. Add a task\n2. Display tasks\n3. Sort tasks by priority\n4. Exit\n";
        std::cin >> choice;

        if (choice == 1) {
            Task t;
            std::cout << "Enter task name: ";
            std::cin.ignore();
            std::getline(std::cin, t.name);
            std::cout << "Enter priority (1: High, 2: Medium, 3: Low): ";
            std::cin >> t.priority;
            tasks.push_back(t);
        } else if (choice == 2) {
            std::cout << "\nYour tasks:\n";
            for (const auto& task : tasks) {
                std::cout << "Task: " << task.name << ", Priority: " << task.priority << "\n";
            }
        } else if (choice == 3) {
            std::sort(tasks.begin(), tasks.end(), compareTasks);
            std::cout << "Tasks sorted by priority!\n";
        }

    } while (choice != 4);

    return 0;
}
