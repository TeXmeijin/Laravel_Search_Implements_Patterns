# Components

このnamespace以下に実験用のソースを実装していくものとします。

## tree

```bash
.
├── ArticlesV1
│   ├── Repositories
│   │   ├── Concretes
│   │   │   └── MySQLArticleRepository.php
│   │   └── Interfaces
│   │       └── ArticleRepositoryInterface.php
│   ├── Services
│   │   └── ArticleService.php
│   └── readme.md
├── ArticlesV2
│   ├── Domain
│   │   ├── Entity
│   │   │   └── Article.php
│   │   ├── Repository
│   │   │   └── ArticleRepositoryInterface.php
│   │   └── ValueObject
│   │       └── ArticleTitle.php
│   ├── Infrastructure
│   │   └── MySQLArticleRepositoryInterface.php
│   ├── UseCase
│   │   ├── CreateArticleUseCase.php
│   │   └── GetArticleListUseCase.php
│   └── readme.md
├── ArticlesV3
│   ├── Domain
│   │   ├── Entity
│   │   │   └── Article.php
│   │   ├── Repository
│   │   │   └── ArticleRepositoryInterface.php
│   │   └── ValueObject
│   │       └── ArticleTitle.php
│   ├── Infrastructure
│   │   ├── MySQLArticleRepositoryInterface.php
│   │   └── QueryService
│   │       └── MySQLGetArticleListQueryService.php
│   ├── UseCase
│   │   ├── CreateArticleUseCase.php
│   │   ├── DTO
│   │   │   └── GetArticleListQueryServiceDTO.php
│   │   └── QueryService
│   │       └── GetArticleListQueryServiceInterface.php
│   └── readme.md
├── ArticlesV4
│   ├── Domain
│   │   ├── Entity
│   │   │   └── Article.php
│   │   ├── Repository
│   │   │   └── ArticleRepositoryInterface.php
│   │   └── ValueObject
│   │       └── ArticleTitle.php
│   ├── Infrastructure
│   │   └── MySQLArticleRepositoryInterface.php
│   ├── UseCase
│   │   ├── CreateArticleUseCase.php
│   │   └── GetArticleListUseCase.php
│   └── readme.md
├── ArticlesV5
│   ├── Repositories
│   │   ├── Concretes
│   │   │   └── MySQLArticleRepository.php
│   │   └── Interfaces
│   │       └── ArticleRepositoryInterface.php
│   ├── UseCase
│   │   ├── CreateArticleUseCase.php
│   │   └── GetArticleListUseCase.php
│   └── readme.md
└── README.md
```

## memo

Componentsという命名はClean Architectureでよく見るので付けたので特に深い意図はない。DDDならContextsとかつけるのかな。Packagesというのも見たことがある。

