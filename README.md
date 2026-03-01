<!-- README.md - Multi-language Project Manager Skill -->

[English](#english) | [中文](#中文) | [日本語](#日本語) | [한국어](#한국어)

---

<div align="center">

# Project Manager Skill

### Claude Code 项目管理技能

*A powerful skill to organize and manage your local development projects*

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/charley-cpu/project-manager-skill)
[![Platform](https://img.shields.io/badge/platform-Windows-green)](https://github.com/charley-cpu/project-manager-skill)

</div>

---

## English

### What is Project Manager?

Project Manager is a Claude Code skill that helps you organize and manage all your local development projects in a unified directory. No more losing track of where your projects are!

### Features

| Feature | Description |
|---------|-------------|
| 📁 Project Indexing | Maintain a list of all projects with names and descriptions |
| 📂 Project Organization | Move scattered projects to a unified directory |
| 🔍 Quick Location | Find any project instantly |
| 💾 Disk Management | Handle large files intelligently (exclude node_modules, output, etc.) |
| 🌐 Multi-language Support | Supports English, Chinese, Japanese, Korean |

### Installation

#### Step 1: Copy the Skill

Copy the entire `project-manager` folder to your Claude Code skills directory:

```
C:\Users\YourUsername\.claude\skills\
```

#### Step 2: Restart Claude Code

Restart your Claude Code application to load the new skill.

### Usage

After installation, you can interact with the skill using natural language:

| Command | Description |
|---------|-------------|
| "Organize my projects" | Scan and organize all projects to the unified directory |
| "Where is my xxx project?" | Find the location of a specific project |
| "Show all projects" | List all your projects |
| "Enter [project name]" | Navigate to a project directory |

### Default Project Directory

```
C:\Users\Administrator\projects\
```

### Configuration

When you first organize projects, you can specify a custom storage location. The skill will:

1. Scan your home directory for project folders
2. Create a unified `projects` directory
3. Copy/move projects to the new location
4. Generate a `PROJECTS.md` index file

### Example

```
User: Organize my projects
Skill: Where would you like to store your projects?
       - Default: C:\Users\Administrator\projects\
       - Or specify a custom path
User: Use the default path
Skill: ✅ Projects organized successfully!
       Found 9 projects:
       - manifestation (显化小程序)
       - vton-app (AI换装小程序)
       - youtube_downloader
       - ...
```

### Requirements

- Claude Code or OpenCLAW
- Windows operating system
- Write permissions to home directory

---

## 中文

### 什么是项目管理器？

项目管理器是一个 Claude Code 技能，帮助你将所有本地开发项目整理到统一的目录中。再也不怕找不到项目了！

### 功能特性

| 功能 | 描述 |
|------|------|
| 📁 项目索引 | 维护所有项目的名称和描述列表 |
| 📂 项目整理 | 将分散的项目移动到统一目录 |
| 🔍 快速定位 | 立即找到任何项目 |
| 💾 磁盘管理 | 智能处理大文件（排除 node_modules、output 等） |
| 🌐 多语言支持 | 支持英文、中文、日文、韩文 |

### 安装步骤

#### 步骤 1：复制技能文件

将整个 `project-manager` 文件夹复制到你的 Claude Code skills 目录：

```
C:\Users\你的用户名\.claude\skills\
```

#### 步骤 2：重启 Claude Code

重启 Claude Code 应用以加载新技能。

### 使用方法

安装后，你可以使用自然语言与技能交互：

| 命令 | 描述 |
|------|------|
| "整理我的项目" | 扫描并整理所有项目到统一目录 |
| "我的xxx项目在哪" | 查找特定项目的位置 |
| "查看所有项目" | 列出所有项目 |
| "进入[项目名]" | 导航到项目目录 |

### 默认项目目录

```
C:\Users\Administrator\projects\
```

### 配置说明

首次整理项目时，你可以指定自定义存储位置。技能会：

1. 扫描主目录查找项目文件夹
2. 创建统一的 `projects` 目录
3. 将项目复制/移动到新位置
4. 生成 `PROJECTS.md` 索引文件

### 示例

```
用户：整理我的项目
技能：你希望把项目存放在哪里？
      - 默认：C:\Users\Administrator\projects\
      - 或指定自定义路径
用户：使用默认路径
技能：✅ 项目整理成功！
      找到 9 个项目：
      - manifestation (显化小程序)
      - vton-app (AI换装小程序)
      - youtube_downloader
      - ...
```

### 环境要求

- Claude Code 或 OpenCLAW
- Windows 操作系统
- 主目录写入权限

---

## 日本語

### プロジェクトマネージャーとは？

プロジェクトマネージャーは、すべてのローカル開発プロジェクトを統一されたディレクトリに整理帮助你管理するClaude Codeスキルです。もうプロジェクトを見失うことはありません！

### 機能

| 機能 | 説明 |
|------|------|
| 📁 プロジェクト索引 | すべてのプロジェクトの名前と説明のリストを維持 |
| 📂 プロジェクト整理 | 散らばったプロジェクトを統一されたディレクトリに移動 |
| 🔍 クイックロケーション | 任意のプロジェクトを即座に見つける |
| 💾 ディスク管理 | 大きなファイルをインテリジェントに処理 |
| 🌐 多言語サポート | 英語、中日本語、韓国語をサポート |

### インストール

#### ステップ1：スキルをコピー

`project-manager` フォルダ全体をClaude Code skillsディレクトリにコピー：

```
C:\Users\あなたのユーザー名\.claude\skills\
```

#### ステップ2：Claude Codeを再起動

Claude Codeアプリケーションを再起動して、新しいスキルをロードします。

### 使用方法

インストール後、自然言語でスキルと対話できます：

| コマンド | 説明 |
|----------|------|
| 「プロジェクトを整理して」 | すべてのプロジェクトをスキャンして統一ディレクトリに移動 |
| 「私のxxxプロジェクトはどこですか」 | 特定のプロジェクトの場所を見つける |
| 「すべてのプロジェクトを表示」 | すべてのプロジェクトをリスト表示 |
| 「[プロジェクト名]に入る」 | プロジェクトディレクトリに移動 |

### デフォルトプロジェクトディレクトリ

```
C:\Users\Administrator\projects\
```

### 設定

初めてプロジェクトを整理する際に、カスタム保存場所を指定できます。スキルは：

1. ホームディレクトリをスキャンしてプロジェクトフォルダを探す
2. 統一された `projects` ディレクトリを作成
3. プロジェクトを新しい場所にコピー/移動
4. `PROJECTS.md` 索引ファイルを生成

---

## 한국어

### 프로젝트 매니저란?

프로젝트 매니저는 모든 로컬 개발 프로젝트를 통합 디렉토리로 구성帮助你 관리하는 Claude Code 스킬입니다. 이제 프로젝트를 잃어버릴 필요가 없습니다!

### 기능

| 기능 | 설명 |
|------|------|
| 📁 프로젝트 인덱싱 | 모든 프로젝트 이름과 설명 목록 유지 |
| 📂 프로젝트 구성 | 흩어진 프로젝트를 통합 디렉토리로 이동 |
| 🔍 빠른 위치 찾기 | 어떤 프로젝트든 즉시 찾기 |
| 💾 디스크 관리 | 큰 파일 지능적으로 처리 |
| 🌐 다국어 지원 | 영어,중국어,일본어,한국어 지원 |

### 설치

#### 1단계: 스킬 복사

전체 `project-manager` 폴더를 Claude Code skills 디렉토리에 복사:

```
C:\Users\사용자 이름\.claude\skills\
```

#### 2단계: Claude Code 재시작

Claude Code 애플리케이션을 다시 시작하여 새 스킬을 로드합니다.

###使用方法

설치 후 자연어로 스킬과 상호작용할 수 있습니다:

| 명령어 | 설명 |
|--------|------|
| "내 프로젝트 정리" | 모든 프로젝트를 스캔하여 통합 디렉토리로 구성 |
| "내 xxx 프로젝트 어디 있어?" | 특정 프로젝트의 위치 찾기 |
| "모든 프로젝트 보기" | 모든 프로젝트 나열 |
| "[프로젝트 이름]으로 이동" | 프로젝트 디렉토리로 이동 |

### 기본 프로젝트 디렉토리

```
C:\Users\Administrator\projects\
```

### 구성

프로젝트를 처음 구성할 때 사용자 지정 저장 위치를 지정할 수 있습니다. 스킬은:

1. 홈 디렉토리를 스캔하여 프로젝트 폴더 찾기
2. 통합된 `projects` 디렉토리 만들기
3. 새 위치로 프로젝트 복사/이동
4. `PROJECTS.md` 인덱스 파일 생성

---

## 🚀 Quick Start

```bash
# Clone this repository
git clone https://github.com/charley-cpu/project-manager-skill.git

# Copy to your Claude Code skills
cp -r project-manager-skill ~/.claude/skills/

# Restart Claude Code and enjoy!
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

MIT License - feel free to use it in your own projects.

---

<div align="center">

**Made with ❤️ by [charley-cpu](https://github.com/charley-cpu)**

</div>
