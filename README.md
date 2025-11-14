# 李慕約顧問課程 Landing Page

這個專案是一個為「李慕約」生成式 AI 策略顧問課程打造的單頁式網站原型，內容包含：
- Hero 區塊與多重 CTA
- 顧問背景與核心數據亮點
- 課程／顧問服務介紹與學習成果
- 六週課程大綱與方案定價
- 社群資源、顧問預約與聯絡資訊

直接開啟 `index.html` 即可預覽設計稿。

## 專案目錄結構

```mermaid
%% Directory Tree
flowchart TD
    A[homepage/] --> B[README.md]
    A --> C[index.html]
    A --> D[2f33bc80-4add-46b8-ad7b-a7abe2dda37e.jpg]
```

## 使用者瀏覽流程

```mermaid
%% Flowchart: User journey through the landing page
flowchart TD
    Start[訪客進入首頁] --> Hero[閱讀 Hero 區塊並選擇 CTA]
    Hero -->|想了解顧問背景| Profile[瀏覽顧問背景與核心數據]
    Hero -->|想了解課程內容| Course[查看課程／服務介紹與學習成果]
    Course --> Outline[檢視六週課程大綱]
    Outline --> Pricing[比較方案定價]
    Profile --> Pricing
    Pricing --> CTA[透過社群連結或表單進行預約／聯絡]
    CTA --> End[完成轉換或後續跟進]
```

## Git 分支示意

```mermaid
%% Git Graph: Simple branching workflow
gitGraph
    commit id: "初始化"
    branch feature/ui-adjustments
    checkout feature/ui-adjustments
    commit id: "版面調整"
    commit id: "CTA 更新"
    checkout main
    commit id: "內容優化"
    merge feature/ui-adjustments
```
