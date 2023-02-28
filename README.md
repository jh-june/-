
# 이력서

## 개요

이름: 이지훈 연락처: 010-3262-6007 이메일: jh~june~\@outlook.com

프로그래밍과 컴퓨터에 관심이 있습니다. 한국에서 경영학을 전공하였으나
2학년을 마친 후 중퇴하였습니다. 지난 1년간 GitHub의 Spacemacs 프로젝트에
지속적으로 관심을 가지고 있습니다. 기술과 지식의 부족으로 인해 코드를
기여하는 것에 아직 어려움을 느끼지만 프로젝트를 학습하며 미래에 기여를
할 수 있기를 희망합니다. Emacs와 Spacemacs를 학습하는 과정에서 텍스트와
시스템을 다루는 능력이 뛰어납니다. 경영학 전공이지만 컴퓨터 시스템
관리와 처리 능력에 대한 이해도가 더 높습니다. 새로운 것을 학습하는 것에
항상 관심을 가지고 있으며 평생 학습자라고 생각합니다.

## 기술

-   텍스트 편집과 시스템을 다루는 것
-   시스템을 관리하는데에 적합한 텍스트 편집기 Emacs와 Vim에 대한 지식과
    경험

## 학력

-   경영학 전공 (한국의 대학, 2학년 중퇴)
-   FRM 재무위험관리사 1차 2차 합격

## 활동

-   Python의 Request라이브러리로 API를 요청, Openpyxl라이브러리로
    Excel파일 관리등의 경험
-   대학교에서 투자론 파생상품론 재무관리론에 데이터 불러오고 10주에
    걸쳐 투자 진행 경험
-   Spacemacs 프로젝트를 이용하고 기여하기 위한 코드를 작성중
-   Lisp, Emacs-Lisp, Python, Java-script 언어 이용

## 자기소개

입사를 하게되어 어느 직책을 맡게되면 일을 빨리 배울 수 있음며 직무를
위해 구체적으로 공부해야될 것이 무엇인지에 대해 파악하고 기초부터 전부
배워나갈 수 있는 것이 저의 강점입니다 많은 곳에 지원을 했지만 전공자가
아니며 코딩 프로젝트를 진행한 경험이 없다는 이유로 항상 거절 당했습니다.
하지만 아무런 이유없이 포트폴리오 이력서를 위한 프로젝트 진행을 하는
것에 대해서는 항상 심리적인 어려움을 느꼈습니다 저는 프로그래밍과
컴퓨터에 관심이 많습니다. 성균관대학교에서 경영학을 전공했지만, 학교를
중퇴한 이후에는 컴퓨터시스템 공부에 열중했습니다. 지난 2년간 GitHub의
Spacemacs라는 프로젝트를 사용하여 시스템에 대한 학습을 진행하고
있습니다. 아직은 코드 기여를 하기 위한 능력에 한참 부족함을 느껴 꾸준히
공부를 하고 있지만 프로젝트를 더욱 깊이 학습하며 미래에 관리를 담당하는
것이 목표입니다 제가 진행해왔던 프로젝트는 항상 전부 개인 프로젝트로
필요성이 느끼다고 생각하여 진행했습니다. 예를 들면 위에 활동으로
설명해드린 Lisp, Emacs-Lisp Python, Java-Script등을 다루는 능력입니다.
Lisp와 Emacs-Lisp는 Spacemacs라는 프로젝트에 기여하기 위해 배웠습니다.
Python은 Excel파일과 API Request를 받기 위해 배웠습니다. 마지막으로
Java-Script는 저의 노트 파일을 쿼리하고 정리하기 위해 배웠습니다.

## 프로젝트 진행 현황

현재 진행중인 프로젝트는 두개로 나누어서 진했했으며 둘 다 장기
프로젝트로 분류했습니다. 하나는 공동체 프로젝트이며 다른 하나는 개인
프로젝트입니다. 하나는 오픈소스 프로젝트이며 다른 하나는 개인
프로젝트이기 때문에 정확한 개요, 목표, 범위, 일정, 예산이 없지만 이번
이력서를 위해 작성하게 됐습니다.

### 프로젝트A

### 프로젝트 개요

프로젝트 공식홈페이지 : <https://www.spacemacs.org/> Github 리파지토리 :
<https://github.com/syl20bnr/spacemacs> 프로젝트 소개 : Spacemacs는
Emacs 편집기를 기반으로 한 편집기 환경입니다. Spacemacs 프로젝트는
편리한 기능을 제공하는 Emacs 편집기를 개선하고, 사용자 친화적인 환경을
제공하기 위한 프로젝트입니다. 이 프로젝트의 목표는 Emacs 사용자들이
Spacemacs를 사용하여 더 쉽게 작업할 수 있도록 돕는 것입니다.

### 프로젝트 목표

-   Spacemacs 레이어 기여
-   Spacemacs 리파지토리 관리

### 프로젝트 범위

Spacemacs 프로젝트의 범위는 다음과 같습니다:

-   Spacemacs .spacemacs.d 설정 파일 개선

### 프로젝트 진행 상황

``` {#.spacemacs 프로젝트 작성 코드 .commonlisp org-language="emacs-lisp"}
;; -*- mode: emacs-lisp; lexical-binding: t -*-
;; This file is loaded by Spacemacs at startup.
;; It must be stored in your home directory.

(defun dotspacemacs/layers ()
  "Layer configuration:
This function should only modify configuration layer settings."
  (setq-default
   ;; Base distribution to use. This is a layer contained in the directory
   ;; `+distribution'. For now available distributions are `spacemacs-base'
   ;; or `spacemacs'. (default 'spacemacs)
   dotspacemacs-distribution 'spacemacs

   ;; Lazy installation of layers (i.e. layers are installed only when a file
   ;; with a supported type is opened). Possible values are `all', `unusedacemacs-configuration-layers'. `nil' disable the lazy
   ;; installation feature and you have to explicitly list a layer in the
   ;; variable `dotspacemacs-configuration-layers' to install it.
   ;; (default 'unused)
   dotspacemacs-enable-lazy-installation 'unused

   ;; If non-nil then Spacemacs will ask for confirmation before installing
   ;; a layer lazily. (default t)
   dotspacemacs-ask-for-lazy-installation t

   ;; List of additional paths where to look for configuration layers.
   ;; Paths must have a trailing slash (i.e. `~/.mycontribs/')
   dotspacemacs-configuration-layer-path '()

   ;; List of configuration layers to load.
   dotspacemacs-configuration-layers
   '(
     ;; ----------------------------------------------------------------
     ;; Example of useful layers you may want to use right away.
     ;; Uncomment some layer names and press `SPC f e R' (Vim style) or
     ;; `M-m f e R' (Emacs style) to install them.
     ;; ----------------------------------------------------------------
     ;; auto-completion
     ;; better-defaults
     emacs-lisp
     ;; git
     helm
     ;; lsp
     ;; markdown
     multiple-cursors
     ;; org
     (shell :variables
            shell-default-height 30
            shell-default-position 'bottom)
     spell-checking
     ;; syntax-checking
     ;; version-control
     treemacs
     html
     emacs-lisp
     helm
     git
     multiple-cursors
     treemacs
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 전자계산기기-명령 개발 언어
     ;;;;;;;;;;;;;;;;;;;;;;;; 함수 언어
     common-lisp
     emacs-lisp
     clojure
     scheme
     ;;;;;;;;;;;;;;;;;;;;;;;; 객체 언어
     c-c++
     ruby
     ;; windows-scripts
     python
     sql
     java
     typescript
     javascript
     ;;;;;;;;;;;;;;;;;;;;;;;; 인공 지능 언어
     (python :variables python-backend 'anaconda)
     go
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;  문서 명기 구조 개발 언어
     latex
     bibtex
     markdown
     org
     deft
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 문서 내부 구조 관리
     ;;spell-checking
     syntax-checking
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 검색
     eww
     search-engine
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 문서 접근 관리
     pdf
     epub
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 문서 공간 관리
     helm
     treemacs
     ibuffer
     pandoc
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 문서 시간 관리
     version-control
     git
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 서식 파일 관리
     auto-completion
     templates
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 종속 관리
     lsp
     docker
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 회계 금융 관리
     finance
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
     helpful
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
     graphviz
     plantuml
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 테마
     themes-megapack
     theming
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 윈도우
     ;; exwm
     ;; eaf
     ;; cmake
     ;; xkcd
     ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;; 보안
     pass
     gnus
     autohotkey

     (plantuml :variables
               plantuml-jar-path "/usr/share/java/plantuml/plantuml.jar"
               org-plantuml-jar-path "/usr/share/java/plantuml/plantuml.jar")

     (deft :variables
            deft-zetteldeft t
            deft-directory "~/notes"
            zetteldeft-home-id "~/notes"
           )

     (org :variables
             org-enable-org-brain-support t
             org-enable-org-contacts-support t
             org-enable-org-contacts-support t
             org-enable-roam-protocol t
             org-enable-roam-support t
             org-enable-roam-ui t
             org-enable-valign t
             org-enable-github-support t
             org-enable-hugo-support t
             org-directory "~/notes"
             org-roam-directory "~/notes/link"
             org-todo-keywords '((sequence "TODO" "|" "DONE"))
             ;; org-todo-keywords '((sequence "TODO" "DOING" "|" "DONE" "NIL" "ERROR"))
             )


     (auto-completion :variables
                      auto-completion-private-snippets-directory "~/.spacemacs.d/snippets"
                     )

     (helm :variables
            helm-position 'right)


     (shell :variables
            shell-default-height 30
            shell-default-position 'right)

     (bibtex :variables
             bibtex-enable-ebib-support t
             ebib-preload-bib-files '("~/.spacemacs.d/notes/papers/bibliography.org")
             ebib-file-search-dirs '("~/.spacemacs.d/notes/papers/bibliography.org")
             ebib-import-directory "~/.spacemacs.d/notes/papers/bibliography.org")

     )


   ;; List of additional packages that will be installed without being wrapped
   ;; in a layer (generally the packages are installed only and should still be
   ;; loaded using load/require/use-package in the user-config section below in
   ;; this file). If you need some configuration for these packages, then
   ;; consider creating a layer. You can also put the configuration in
   ;; `dotspacemacs/user-config'. To use a local version of a package, use the
   ;; `:location' property: '(your-package :location "~/path/to/your-package/")
   ;; Also include the dependencies as they will not be resolved automatically.
   dotspacemacs-additional-packages '(
                                      ;;excel-mode
                                      ;;dotspacemacs-additional-packages
                                      ;;'(copilot :location (recipe
                                                            ;;:fetcher github
                                                            ;;:repo "zerolfx/copilot.el"
                                                            ;;:files ("*.el" "dist")))
                                      ;;(chatgpt :location (recipe
                                                          ;;:fetcher github
                                                          ;;:repo "joshcho/ChatGPT.el"))
                                      ;; other additional packages...
                                      ledger-import
                                      flycheck-hledger
                                      calibredb
                                      nov
                                      sicp
                                      ob-powershell
                                      hledger-mode
                                      )

   ;; A list of packages that cannot be updated.
   dotspacemacs-frozen-packages '()

   ;; A list of packages that will not be installed and loaded.
   dotspacemacs-excluded-packages '()

   ;; Defines the behaviour of Spacemacs when installing packages.
   ;; Possible values are `used-only', `used-but-keep-unused' and `all'.
   ;; `used-only' installs only explicitly used packages and deletes any unused
   ;; packages as well as their unused dependencies. `used-but-keep-unused'
   ;; installs only the used packages but won't delete unused ones. `all'
   ;; installs *all* packages supported by Spacemacs and never uninstalls them.
   ;; (default is `used-only')
   dotspacemacs-install-packages 'used-only))

(defun dotspacemacs/init ()
  "Initialization:
This function is called at the very beginning of Spacemacs startup,
before layer configuration.
It should only modify the values of Spacemacs settings."
  ;; This setq-default sexp is an exhaustive list of all the supported
  ;; spacemacs settings.
  (setq-default
   ;; If non-nil then enable support for the portable dumper. You'll need to
   ;; compile Emacs 27 from source following the instructions in file
   ;; EXPERIMENTAL.org at to root of the git repository.
   ;;
   ;; WARNING: pdumper does not work with Native Compilation, so it's disabled
   ;; regardless of the following setting when native compilation is in effect.
   ;;
   ;; (default nil)
   dotspacemacs-enable-emacs-pdumper nil

   ;; Name of executable file pointing to emacs 27+. This executable must be
   ;; in your PATH.
   ;; (default "emacs")
   dotspacemacs-emacs-pdumper-executable-file "emacs"

   ;; Name of the Spacemacs dump file. This is the file will be created by the
   ;; portable dumper in the cache directory under dumps sub-directory.
   ;; To load it when starting Emacs add the parameter `--dump-file'
   ;; when invoking Emacs 27.1 executable on the command line, for instance:
   ;;   ./emacs --dump-file=$HOME/.emacs.d/.cache/dumps/spacemacs-27.1.pdmp
   ;; (default (format "spacemacs-%s.pdmp" emacs-version))
   dotspacemacs-emacs-dumper-dump-file (format "spacemacs-%s.pdmp" emacs-version)

   ;; If non-nil ELPA repositories are contacted via HTTPS whenever it's
   ;; possible. Set it to nil if you have no way to use HTTPS in your
   ;; environment, otherwise it is strongly recommended to let it set to t.
   ;; This variable has no effect if Emacs is launched with the parameter
   ;; `--insecure' which forces the value of this variable to nil.
   ;; (default t)
   dotspacemacs-elpa-https t

   ;; Maximum allowed time in seconds to contact an ELPA repository.
   ;; (default 5)
   dotspacemacs-elpa-timeout 5

   ;; Set `gc-cons-threshold' and `gc-cons-percentage' when startup finishes.
   ;; This is an advanced option and should not be changed unless you suspect
   ;; performance issues due to garbage collection operations.
   ;; (default '(100000000 0.1))
   dotspacemacs-gc-cons '(100000000 0.1)

   ;; Set `read-process-output-max' when startup finishes.
   ;; This defines how much data is read from a foreign process.
   ;; Setting this >= 1 MB should increase performance for lsp servers
   ;; in emacs 27.
   ;; (default (* 1024 1024))
   dotspacemacs-read-process-output-max (* 1024 1024)

   ;; If non-nil then Spacelpa repository is the primary source to install
   ;; a locked version of packages. If nil then Spacemacs will install the
   ;; latest version of packages from MELPA. Spacelpa is currently in
   ;; experimental state please use only for testing purposes.
   ;; (default nil)
   dotspacemacs-use-spacelpa nil

   ;; If non-nil then verify the signature for downloaded Spacelpa archives.
   ;; (default t)
   dotspacemacs-verify-spacelpa-archives t

   ;; If non-nil then spacemacs will check for updates at startup
   ;; when the current branch is not `develop'. Note that checking for
   ;; new versions works via git commands, thus it calls GitHub services
   ;; whenever you start Emacs. (default nil)
   dotspacemacs-check-for-update nil

   ;; If non-nil, a form that evaluates to a package directory. For example, to
   ;; use different package directories for different Emacs versions, set this
   ;; to `emacs-version'. (default 'emacs-version)
   dotspacemacs-elpa-subdirectory 'emacs-version

   ;; One of `vim', `emacs' or `hybrid'.
   ;; `hybrid' is like `vim' except that `insert state' is replaced by the
   ;; `hybrid state' with `emacs' key bindings. The value can also be a list
   ;; with `:variables' keyword (similar to layers). Check the editing styles
   ;; section of the documentation for details on available variables.
   ;; (default 'vim)
   dotspacemacs-editing-style 'vim

   ;; If non-nil show the version string in the Spacemacs buffer. It will
   ;; appear as (spacemacs version)@(emacs version)
   ;; (default t)
   dotspacemacs-startup-buffer-show-version t

   ;; Specify the startup banner. Default value is `official', it displays
   ;; the official spacemacs logo. An integer value is the index of text
   ;; banner, `random' chooses a random text banner in `core/banners'
   ;; directory. A string value must be a path to an image format supported
   ;; by your Emacs build.
   ;; If the value is nil then no banner is displayed. (default 'official)
   dotspacemacs-startup-banner 'random

   ;; Scale factor controls the scaling (size) of the startup banner. Default
   ;; value is `auto' for scaling the logo automatically to fit all buffer
   ;; contents, to a maximum of the full image height and a minimum of 3 line
   ;; heights. If set to a number (int or float) it is used as a constant
   ;; scaling factor for the default logo size.
   dotspacemacs-startup-banner-scale 'auto

   ;; List of items to show in startup buffer or an association list of
   ;; the form `(list-type . list-size)`. If nil then it is disabled.
   ;; Possible values for list-type are:
   ;; `recents' `recents-by-project' `bookmarks' `projects' `agenda' `todos'.
   ;; List sizes may be nil, in which case
   ;; `spacemacs-buffer-startup-lists-length' takes effect.
   ;; The exceptional case is `recents-by-project', where list-type must be a
   ;; pair of numbers, e.g. `(recents-by-project . (7 .  5))', where the first
   ;; number is the project limit and the second the limit on the recent files
   ;; within a project.
   dotspacemacs-startup-lists '((recents . 5)
                                (projects . 7))

   ;; True if the home buffer should respond to resize events. (default t)
   dotspacemacs-startup-buffer-responsive t

   ;; Show numbers before the startup list lines. (default t)
   dotspacemacs-show-startup-list-numbers t

   ;; The minimum delay in seconds between number key presses. (default 0.4)
   dotspacemacs-startup-buffer-multi-digit-delay 0.4

   ;; If non-nil, show file icons for entries and headings on Spacemacs home buffer.
   ;; This has no effect in terminal or if "all-the-icons" package or the font
   ;; is not installed. (default nil)
   dotspacemacs-startup-buffer-show-icons nil

   ;; Default major mode for a new empty buffer. Possible values are mode
   ;; names such as `text-mode'; and `nil' to use Fundamental mode.
   ;; (default `text-mode')
   dotspacemacs-new-empty-buffer-major-mode 'text-mode

   ;; Default major mode of the scratch buffer (default `text-mode')
   dotspacemacs-scratch-mode 'text-mode

   ;; If non-nil, *scratch* buffer will be persistent. Things you write down in
   ;; *scratch* buffer will be saved and restored automatically.
   dotspacemacs-scratch-buffer-persistent nil

   ;; If non-nil, `kill-buffer' on *scratch* buffer
   ;; will bury it instead of killing.
   dotspacemacs-scratch-buffer-unkillable nil

   ;; Initial message in the scratch buffer, such as "Welcome to Spacemacs!"
   ;; (default nil)
   dotspacemacs-initial-scratch-message nil

   ;; List of themes, the first of the list is loaded when spacemacs starts.
   ;; Press `SPC T n' to cycle to the next theme in the list (works great
   ;; with 2 themes variants, one dark and one light)
   dotspacemacs-themes '(gruvbox-dark-hard
                         spacemacs-dark
                         spacemacs-light)

   ;; Set the theme for the Spaceline. Supported themes are `spacemacs',
   ;; `all-the-icons', `custom', `doom', `vim-powerline' and `vanilla'. The
   ;; first three are spaceline themes. `doom' is the doom-emacs mode-line.
   ;; `vanilla' is default Emacs mode-line. `custom' is a user defined themes,
   ;; refer to the DOCUMENTATION.org for more info on how to create your own
   ;; spaceline theme. Value can be a symbol or list with additional properties.
   ;; (default '(spacemacs :separator wave :separator-scale 1.5))
   dotspacemacs-mode-line-theme '(spacemacs :separator wave :separator-scale 1.5)

   ;; If non-nil the cursor color matches the state color in GUI Emacs.
   ;; (default t)
   dotspacemacs-colorize-cursor-according-to-state t

   ;; Default font or prioritized list of fonts. The `:size' can be specified as
   ;; a non-negative integer (pixel size), or a floating-point (point size).
   ;; Point size is recommended, because it's device independent. (default 10.0)
   dotspacemacs-default-font '("Cascadia Code"
                               :size 10.0
                               :weight normal
                               :width normal)

   ;; The leader key (default "SPC")
   dotspacemacs-leader-key "SPC"

   ;; The key used for Emacs commands `M-x' (after pressing on the leader key).
   ;; (default "SPC")
   dotspacemacs-emacs-command-key "SPC"

   ;; The key used for Vim Ex commands (default ":")
   dotspacemacs-ex-command-key ":"

   ;; The leader key accessible in `emacs state' and `insert state'
   ;; (default "M-m")
   dotspacemacs-emacs-leader-key "M-m"

   ;; Major mode leader key is a shortcut key which is the equivalent of
   ;; pressing `<leader> m`. Set it to `nil` to disable it. (default ",")
   dotspacemacs-major-mode-leader-key ","

   ;; Major mode leader key accessible in `emacs state' and `insert state'.
   ;; (default "C-M-m" for terminal mode, "<M-return>" for GUI mode).
   ;; Thus M-RET should work as leader key in both GUI and terminal modes.
   ;; C-M-m also should work in terminal mode, but not in GUI mode.
   dotspacemacs-major-mode-emacs-leader-key (if window-system "<M-return>" "C-M-m")

   ;; These variables control whether separate commands are bound in the GUI to
   ;; the key pairs `C-i', `TAB' and `C-m', `RET'.
   ;; Setting it to a non-nil value, allows for separate commands under `C-i'
   ;; and TAB or `C-m' and `RET'.
   ;; In the terminal, these pairs are generally indistinguishable, so this only
   ;; works in the GUI. (default nil)
   dotspacemacs-distinguish-gui-tab nil

   ;; Name of the default layout (default "Default")
   dotspacemacs-default-layout-name "Default"

   ;; If non-nil the default layout name is displayed in the mode-line.
   ;; (default nil)
   dotspacemacs-display-default-layout nil

   ;; If non-nil then the last auto saved layouts are resumed automatically upon
   ;; start. (default nil)
   dotspacemacs-auto-resume-layouts nil

   ;; If non-nil, auto-generate layout name when creating new layouts. Only has
   ;; effect when using the "jump to layout by number" commands. (default nil)
   dotspacemacs-auto-generate-layout-names nil

   ;; Size (in MB) above which spacemacs will prompt to open the large file
   ;; literally to avoid performance issues. Opening a file literally means that
   ;; no major mode or minor modes are active. (default is 1)
   dotspacemacs-large-file-size 1

   ;; Location where to auto-save files. Possible values are `original' to
   ;; auto-save the file in-place, `cache' to auto-save the file to another
   ;; file stored in the cache directory and `nil' to disable auto-saving.
   ;; (default 'cache)
   dotspacemacs-auto-save-file-location 'cache

   ;; Maximum number of rollback slots to keep in the cache. (default 5)
   dotspacemacs-max-rollback-slots 5

   ;; If non-nil, the paste transient-state is enabled. While enabled, after you
   ;; paste something, pressing `C-j' and `C-k' several times cycles through the
   ;; elements in the `kill-ring'. (default nil)
   dotspacemacs-enable-paste-transient-state nil

   ;; Which-key delay in seconds. The which-key buffer is the popup listing
   ;; the commands bound to the current keystroke sequence. (default 0.4)
   dotspacemacs-which-key-delay 0.4

   ;; Which-key frame position. Possible values are `right', `bottom' and
   ;; `right-then-bottom'. right-then-bottom tries to display the frame to the
   ;; right; if there is insufficient space it displays it at the bottom.
   ;; (default 'bottom)
   dotspacemacs-which-key-position 'right

   ;; Control where `switch-to-buffer' displays the buffer. If nil,
   ;; `switch-to-buffer' displays the buffer in the current window even if
   ;; another same-purpose window is available. If non-nil, `switch-to-buffer'
   ;; displays the buffer in a same-purpose window even if the buffer can be
   ;; displayed in the current window. (default nil)
   dotspacemacs-switch-to-buffer-prefers-purpose nil

   ;; If non-nil a progress bar is displayed when spacemacs is loading. This
   ;; may increase the boot time on some systems and emacs builds, set it to
   ;; nil to boost the loading time. (default t)
   dotspacemacs-loading-progress-bar t

   ;; If non-nil the frame is fullscreen when Emacs starts up. (default nil)
   ;; (Emacs 24.4+ only)
   dotspacemacs-fullscreen-at-startup nil

   ;; If non-nil `spacemacs/toggle-fullscreen' will not use native fullscreen.
   ;; Use to disable fullscreen animations in OSX. (default nil)
   dotspacemacs-fullscreen-use-non-native nil

   ;; If non-nil the frame is maximized when Emacs starts up.
   ;; Takes effect only if `dotspacemacs-fullscreen-at-startup' is nil.
   ;; (default t) (Emacs 24.4+ only)
   dotspacemacs-maximized-at-startup t

   ;; If non-nil the frame is undecorated when Emacs starts up. Combine this
   ;; variable with `dotspacemacs-maximized-at-startup' to obtain fullscreen
   ;; without external boxes. Also disables the internal border. (default nil)
   dotspacemacs-undecorated-at-startup nil

   ;; A value from the range (0..100), in increasing opacity, which describes
   ;; the transparency level of a frame when it's active or selected.
   ;; Transparency can be toggled through `toggle-transparency'. (default 90)
   dotspacemacs-active-transparency 90

   ;; A value from the range (0..100), in increasing opacity, which describes
   ;; the transparency level of a frame when it's inactive or deselected.
   ;; Transparency can be toggled through `toggle-transparency'. (default 90)
   dotspacemacs-inactive-transparency 90

   ;; A value from the range (0..100), in increasing opacity, which describes the
   ;; transparency level of a frame background when it's active or selected. Transparency
   ;; can be toggled through `toggle-background-transparency'. (default 90)
   dotspacemacs-background-transparency 90

   ;; If non-nil show the titles of transient states. (default t)
   dotspacemacs-show-transient-state-title t

   ;; If non-nil show the color guide hint for transient state keys. (default t)
   dotspacemacs-show-transient-state-color-guide t

   ;; If non-nil unicode symbols are displayed in the mode line.
   ;; If you use Emacs as a daemon and wants unicode characters only in GUI set
   ;; the value to quoted `display-graphic-p'. (default t)
   dotspacemacs-mode-line-unicode-symbols t

   ;; If non-nil smooth scrolling (native-scrolling) is enabled. Smooth
   ;; scrolling overrides the default behavior of Emacs which recenters point
   ;; when it reaches the top or bottom of the screen. (default t)
   dotspacemacs-smooth-scrolling t

   ;; Show the scroll bar while scrolling. The auto hide time can be configured
   ;; by setting this variable to a number. (default t)
   dotspacemacs-scroll-bar-while-scrolling t

   ;; Control line numbers activation.
   ;; If set to `t', `relative' or `visual' then line numbers are enabled in all
   ;; `prog-mode' and `text-mode' derivatives. If set to `relative', line
   ;; numbers are relative. If set to `visual', line numbers are also relative,
   ;; but only visual lines are counted. For example, folded lines will not be
   ;; counted and wrapped lines are counted as multiple lines.
   ;; This variable can also be set to a property list for finer control:
   ;; '(:relative nil
   ;;   :visual nil
   ;;   :disabled-for-modes dired-mode
   ;;                       doc-view-mode
   ;;                       markdown-mode
   ;;                       org-mode
   ;;                       pdf-view-mode
   ;;                       text-mode
   ;;   :size-limit-kb 1000)
   ;; When used in a plist, `visual' takes precedence over `relative'.
   ;; (default nil)
   dotspacemacs-line-numbers nil

   ;; Code folding method. Possible values are `evil', `origami' and `vimish'.
   ;; (default 'evil)
   dotspacemacs-folding-method 'evil

   ;; If non-nil and `dotspacemacs-activate-smartparens-mode' is also non-nil,
   ;; `smartparens-strict-mode' will be enabled in programming modes.
   ;; (default nil)
   dotspacemacs-smartparens-strict-mode nil

   ;; If non-nil smartparens-mode will be enabled in programming modes.
   ;; (default t)
   dotspacemacs-activate-smartparens-mode t

   ;; If non-nil pressing the closing parenthesis `)' key in insert mode passes
   ;; over any automatically added closing parenthesis, bracket, quote, etc...
   ;; This can be temporary disabled by pressing `C-q' before `)'. (default nil)
   dotspacemacs-smart-closing-parenthesis nil

   ;; Select a scope to highlight delimiters. Possible values are `any',
   ;; `current', `all' or `nil'. Default is `all' (highlight any scope and
   ;; emphasis the current one). (default 'all)
   dotspacemacs-highlight-delimiters 'all

   ;; If non-nil, start an Emacs server if one is not already running.
   ;; (default nil)
   dotspacemacs-enable-server nil

   ;; Set the emacs server socket location.
   ;; If nil, uses whatever the Emacs default is, otherwise a directory path
   ;; like \"~/.emacs.d/server\". It has no effect if
   ;; `dotspacemacs-enable-server' is nil.
   ;; (default nil)
   dotspacemacs-server-socket-dir nil

   ;; If non-nil, advise quit functions to keep server open when quitting.
   ;; (default nil)
   dotspacemacs-persistent-server nil

   ;; List of search tool executable names. Spacemacs uses the first installed
   ;; tool of the list. Supported tools are `rg', `ag', `pt', `ack' and `grep'.
   ;; (default '("rg" "ag" "pt" "ack" "grep"))
   dotspacemacs-search-tools '("rg" "ag" "pt" "ack" "grep")

   ;; Format specification for setting the frame title.
   ;; %a - the `abbreviated-file-name', or `buffer-name'
   ;; %t - `projectile-project-name'
   ;; %I - `invocation-name'
   ;; %S - `system-name'
   ;; %U - contents of $USER
   ;; %b - buffer name
   ;; %f - visited file name
   ;; %F - frame name
   ;; %s - process status
   ;; %p - percent of buffer above top of window, or Top, Bot or All
   ;; %P - percent of buffer above bottom of window, perhaps plus Top, or Bot or All
   ;; %m - mode name
   ;; %n - Narrow if appropriate
   ;; %z - mnemonics of buffer, terminal, and keyboard coding systems
   ;; %Z - like %z, but including the end-of-line format
   ;; If nil then Spacemacs uses default `frame-title-format' to avoid
   ;; performance issues, instead of calculating the frame title by
   ;; `spacemacs/title-prepare' all the time.
   ;; (default "%I@%S")
   dotspacemacs-frame-title-format "%I@%S"

   ;; Format specification for setting the icon title format
   ;; (default nil - same as frame-title-format)
   dotspacemacs-icon-title-format nil

   ;; Color highlight trailing whitespace in all prog-mode and text-mode derived
   ;; modes such as c++-mode, python-mode, emacs-lisp, html-mode, rst-mode etc.
   ;; (default t)
   dotspacemacs-show-trailing-whitespace t

   ;; Delete whitespace while saving buffer. Possible values are `all'
   ;; to aggressively delete empty line and long sequences of whitespace,
   ;; `trailing' to delete only the whitespace at end of lines, `changed' to
   ;; delete only whitespace for changed lines or `nil' to disable cleanup.
   ;; (default nil)
   dotspacemacs-whitespace-cleanup nil

   ;; If non-nil activate `clean-aindent-mode' which tries to correct
   ;; virtual indentation of simple modes. This can interfere with mode specific
   ;; indent handling like has been reported for `go-mode'.
   ;; If it does deactivate it here.
   ;; (default t)
   dotspacemacs-use-clean-aindent-mode t

   ;; Accept SPC as y for prompts if non-nil. (default nil)
   dotspacemacs-use-SPC-as-y nil

   ;; If non-nil shift your number row to match the entered keyboard layout
   ;; (only in insert state). Currently supported keyboard layouts are:
   ;; `qwerty-us', `qwertz-de' and `querty-ca-fr'.
   ;; New layouts can be added in `spacemacs-editing' layer.
   ;; (default nil)
   dotspacemacs-swap-number-row nil

   ;; Either nil or a number of seconds. If non-nil zone out after the specified
   ;; number of seconds. (default nil)
   dotspacemacs-zone-out-when-idle nil

   ;; Run `spacemacs/prettify-org-buffer' when
   ;; visiting README.org files of Spacemacs.
   ;; (default nil)
   dotspacemacs-pretty-docs nil

   ;; If nil the home buffer shows the full path of agenda items
   ;; and todos. If non-nil only the file name is shown.
   dotspacemacs-home-shorten-agenda-source nil

   ;; If non-nil then byte-compile some of Spacemacs files.
   dotspacemacs-byte-compile nil))

(defun dotspacemacs/user-env ()
  "Environment variables setup.
This function defines the environment variables for your Emacs session. By
default it calls `spacemacs/load-spacemacs-env' which loads the environment
variables declared in `~/.spacemacs.env' or `~/.spacemacs.d/.spacemacs.env'.
See the header of this file for more information."
  (spacemacs/load-spacemacs-env)
)

(defun dotspacemacs/user-init ()
  "Initialization for user code:
This function is called immediately after `dotspacemacs/init', before layer
configuration.
It is mostly for variables that should be set before packages are loaded.
If you are unsure, try setting them in `dotspacemacs/user-config' first."
)


(defun dotspacemacs/user-load ()
  "Library to load while dumping.
This function is called only while dumping Spacemacs configuration. You can
`require' or `load' the libraries of your choice that will be included in the
dump."
)


(defun dotspacemacs/user-config ()
  "Configuration for user code:
This function is called at the very end of Spacemacs startup, after layer
configuration.
Put your configuration code here, except for variables that should be set
before packages are loaded."



  (setq org-toggle-inline-images t)

  ;;(setq org-src-fontify-natively t)
  ;;(add-to-list 'org-src-lang-modes '("CWEB" . c-mode))

  ;;(org-babel-do-load-languages
   ;;'org-babel-load-languages
   ;;'((latex . t)))

  ;;(setq dired-listing-switches "-alh --group-directories-first")
;;
  ;;(with-eval-after-load 'company
    ;;;; disable inline previews
    ;;(delq 'company-preview-if-just-one-frontend company-frontends))
  ;;(with-eval-after-load 'copilot
    ;;(define-key copilot-completion-map (kbd "<tab>") 'copilot-accept-completion)
    ;;(define-key copilot-completion-map (kbd "TAB") 'copilot-accept-completion))

  ;;(add-hook 'prog-mode-hook 'copilot-mode)
;;
  ;;(define-key evil-insert-state-map (kbd "C-<tab>") 'copilot-accept-completion-by-word)
  ;;(define-key evil-insert-state-map (kbd "C-TAB") 'copilot-accept-completion-by-word)



  ;;(require 'python)
  ;;(setq chatgpt-repo-path (expand-file-name "chatgpt/" quelpa-build-dir))
  ;;(global-set-key (kbd "C-c q") #'chatgpt-query)



  ;; C 언어에 대한 org-babel-execute 함수 정의
  (require 'ob)
  (add-to-list 'org-babel-tangle-lang-exts '("c" . "c"))

  (defun org-babel-execute:c (body params)
    "Execute a block of C code with org-babel.
This function is called by `org-babel-execute-src-block'."
    (let* ((processed-params (org-babel-process-params params))
           (tmp-src-file (org-babel-temp-file "c-src-" ".c"))
           (tmp-out-file (org-babel-temp-file "c-out-" ".out"))
           (cmd (format "gcc -o %s %s && %s"
                        tmp-out-file
                        tmp-src-file
                        tmp-out-file)))
      (with-temp-file tmp-src-file (insert body))
      (org-babel-eval cmd "")
      (org-babel-eval (concat tmp-out-file " && rm -f " tmp-out-file) "")))

  (setq default-input-method "fcitx")
  (require 'info+)

  (add-hook 'org-mode-hook (lambda () (electric-indent-local-mode -1)))

  (defun copy-previous-error-code ()
    "Copy the error code from the previous message in the *Messages* buffer."
    (interactive)
    (with-current-buffer "*Messages*"
      (next-error 1)
      (move-beginning-of-line nil)
      (set-mark (point))
      (previous-line)
      (move-end-of-line nil)
      (copy-region-as-kill (region-beginning) (region-end)))
    (message "Error code copied to clipboard."))
  (global-set-key (kbd "C-c C-e") 'copy-previous-error-code)

  (setq bibtex-completion-bibliography '("~/.spacemacs.d/notes/Bibliography_Managing")
        bibtex-completion-library-path "~/.spacemacs.d/notes/Bibliography_Managing"
        bibtex-completion-notes-path  "~/.spacemacs.d/notes/Bibliography_Managing")


;-------------------------- epub configuration

  (defun my-nov-font-setup ()
    (face-remap-add-relative 'variable-pitch :family "Helvetica"
                             :height 1.0))
  (add-hook 'nov-mode-hook 'my-nov-font-setup)

  (setq pdf-view-restore-filename  "~/.spacemacs.d/notes")

;--------------------------  library management


  (setq-default python-indent-offset 4)
  ;; require
  (require 'calibredb)
  (setq calibredb-root-dir "~/notes/libraries")
  (setq calibredb-db-dir (expand-file-name "metadata.db" calibredb-root-dir))
  ;; use-package
  (use-package calibredb)
   :defer t
   :config
   (setq calibredb-root-dir "~/notes/libraries")
  (setq calibredb-db-dir (expand-file-name "metadata.db" calibredb-root-dir))
  ;; support with org-ref
  ;; (require 'org-ref)
  ;; (setq calibredb-ref-default-bibliography (concat (file-name-as-directory calibredb-root-dir) "catalog.bib"))
  ;; (add-to-list 'org-ref-default-bibliography calibredb-ref-default-bibliography)
  ;; (setq org-ref-get-pdf-filename-function 'org-ref-get-mendeley-filename)


;--------------------------  kbd management           prefix - o

;;  (spacemacs/declare-prefix "o" "june-open")
;;  (spacemacs/set-leader-keys "oq" ')
;;  (spacemacs/set-leader-keys "ow" ')
 (spacemacs/set-leader-keys "oe" 'eshell)
 (spacemacs/set-leader-keys "or" 'replace-regexp)
 (spacemacs/set-leader-keys "ot" 'helm-yas-create-snippet-on-region)
 (spacemacs/set-leader-keys "oy" 'org-copy-visible)
;;  (spacemacs/set-leader-keys "ou" ')
 (spacemacs/set-leader-keys "oi" 'yas-snippet-insert)
 (spacemacs/set-leader-keys "oo" 'yas-new-snippet)

;;  (spacemacs/set-leader-keys "op" ')
;;  (spacemacs/set-leader-keys "oa" ')
  (spacemacs/set-leader-keys "os" 'smartparens-mode)
;;  (spacemacs/set-leader-keys "od" 'helm-bookmarks)
;;  (spacemacs/set-leader-keys "of" ')
;;  (spacemacs/set-leader-keys "og" ')
;;  (spacemacs/set-leader-keys "oh" ')
;;  (spacemacs/set-leader-keys "oj" ')
;;  (spacemacs/set-leader-keys "ok" ')
  (spacemacs/set-leader-keys "ol" 'calibredb)
  (spacemacs/set-leader-keys "o;" 'helm-bookmarks)
;;  (spacemacs/set-leader-keys "o'" ')

;;  (spacemacs/set-leader-keys "oz" ')
;;  (spacemacs/set-leader-keys "ox" ')
 (spacemacs/set-leader-keys "oc" 'customize) ; switched from calibredb to customize as the concept of library seems to be more importnat
;;  (spacemacs/set-leader-keys "ov" ')
;;  (spacemacs/set-leader-keys "ob" ')
;;  (spacemacs/set-leader-keys "on" ')
;;  (spacemacs/set-leader-keys "om" ')
;;  (spacemacs/set-leader-keys "o," ')
;;  (spacemacs/set-leader-keys "o>" ')
;;  (spacemacs/set-leader-keys "o/" ')


;--------------------------  kbd management           prefix - d

(spacemacs/declare-prefix "d" "zettel-deft die-had")
;;  (spacemacs/set-leader-keys "dq" ')
;;  (spacemacs/set-leader-keys "dw" ')
;;  (spacemacs/set-leader-keys "de" ')
(spacemacs/set-leader-keys "dr" 'org-roam-capture)
;;  (spacemacs/set-leader-keys "dt" ')
;;  (spacemacs/set-leader-keys "dy" ')
;;  (spacemacs/set-leader-keys "du" ')
;;  (spacemacs/set-leader-keys "di" ')
;;  (spacemacs/set-leader-keys "do" ')

;;  (spacemacs/set-leader-keys "dp" '
;;  (spacemacs/set-leader-keys "da" ')
;;  (spacemacs/set-leader-keys "ds" ')
(spacemacs/set-leader-keys "dd" 'deft)
(spacemacs/set-leader-keys "df" 'zetteldeft-find-file)
;;  (spacemacs/set-leader-keys "dg" ')
;;  (spacemacs/set-leader-keys "dh" ')
;;  (spacemacs/set-leader-keys "dj" ')
;;  (spacemacs/set-leader-keys "dk" ')
;;  (spacemacs/set-leader-keys "dl" ')
;;  (spacemacs/set-leader-keys "d;" ')
;;  (spacemacs/set-leader-keys "d'" ')

;;  (spacemacs/set-leader-keys "dz" ')
;;  (spacemacs/set-leader-keys "dx" ')
;;  (spacemacs/set-leader-keys "dc" ')
;;  (spacemacs/set-leader-keys "dv" ')
;;  (spacemacs/set-leader-keys "db" ')
;;  (spacemacs/set-leader-keys "dn" ')
 (spacemacs/set-leader-keys "dm" 'zetteldeft-new-file)
;;  (spacemacs/set-leader-keys "d," ')
;;  (spacemacs/set-leader-keys "d>" ')
;;  (spacemacs/set-leader-keys "d/" ')


;--------------------------  kbd management              prefix - d

;;  (spacemacs/declare-prefix "d" "deft")
;;  (spacemacs/set-leader-keys "dq" ')
;;  (spacemacs/set-leader-keys "dw" ')
;;  (spacemacs/set-leader-keys "de" ')
;;  (spacemacs/set-leader-keys "dr" ')
;;  (spacemacs/set-leader-keys "dt" ')
;;  (spacemacs/set-leader-keys "dy" ')
;;  (spacemacs/set-leader-keys "du" ')
;;  (spacemacs/set-leader-keys "di" ')
;;  (spacemacs/set-leader-keys "do" ')

;;  (spacemacs/set-leader-keys "dp" '
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')
;;  (spacemacs/set-leader-keys "od" ')

;;  (spacemacs/set-leader-keys "dz" ')
;;  (spacemacs/set-leader-keys "dx" ')
;;    (spacemacs/set-leader-keys "dc" 'customize)
;;  (spacemacs/set-leader-keys "dv" ')
;;  (spacemacs/set-leader-keys "db" ')
;;  (spacemacs/set-leader-keys "dn" ')
;;  (spacemacs/set-leader-keys "dm" ')
;;  (spacemacs/set-leader-keys "d," ')
;;  (spacemacs/set-leader-keys "d>" ')
;;  (spacemacs/set-leader-keys "d/" ')


;--------------------------  kbd management  oo

;;  (spacemacs/declare-prefix "oo" "june-open-opwn")
;;  (spacemacs/set-leader-keys "ooq" ')
;;  (spacemacs/set-leader-keys "oow" ')
;;  (spacemacs/set-leader-keys "ooe" ')
;;  (spacemacs/set-leader-keys "oor" ')
;;  (spacemacs/set-leader-keys "oot" ')
;;  (spacemacs/set-leader-keys "ooy" ')
;;  (spacemacs/set-leader-keys "oou" ')
;;  (spacemacs/set-leader-keys "ooi" ')
;;  (spacemacs/set-leader-keys "ooo" ')

;;  (spacemacs/set-leader-keys "oop" ')
;;  (spacemacs/set-leader-keys "ooa" ')
;;  (spacemacs/set-leader-keys "oos" ')
;;  (spacemacs/set-leader-keys "ood" ')
;;  (spacemacs/set-leader-keys "oof" ')
;;  (spacemacs/set-leader-keys "oog" ')
;;  (spacemacs/set-leader-keys "ooh" ')
;;  (spacemacs/set-leader-keys "ooj" ')
;;  (spacemacs/set-leader-keys "ook" ')
;;  (spacemacs/set-leader-keys "ool" ')
;;  (spacemacs/set-leader-keys "oo;" ')
;;  (spacemacs/set-leader-keys "oo'" ')

;;  (spacemacs/set-leader-keys "ooz" ')
;;  (spacemacs/set-leader-keys "oox" ')
;;  (spacemacs/set-leader-keys "ooc" ')
;;  (spacemacs/set-leader-keys "oov" ')
;;  (spacemacs/set-leader-keys "oob" ')
;;  (spacemacs/set-leader-keys "oon" ')
;;  (spacemacs/set-leader-keys "oom" ')
;;  (spacemacs/set-leader-keys "oo," ')
;;  (spacemacs/set-leader-keys "oo>" ')
;;  (spacemacs/set-leader-keys "oo/" ')

;--------------------------  kbd management           mode

;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "q" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "w" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "e" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "r" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "t" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "y" ' )
(spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "i" 'calibredb-view)
(spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "o" 'calibredb-find-file)
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "p" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "\" ' )

(spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "a" 'calibredb-add)
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "s" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "d" ' )
(spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "f" 'calibredb-open-file-with-default-tool)
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "g" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "h" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "j" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "k" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "l" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode ";" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "'" ' )

;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "z" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "x" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "c" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "v" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "b" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "n" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "m" ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "," ' )
;; (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "." ' )
(spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "/" 'calibredb-search-live-filter)

 (spacemacs/declare-prefix-for-mode 'calibredb-search-mode "s" "sort")
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "si" 'calibredb-sort-by-id)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "st" 'calibredb-sort-by-tag)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "sd" 'calibredb-sort-by-date)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "ss" 'calibredb-sort-by-size)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "st" 'calibredb-sort-by-title)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "sf" 'calibredb-sort-by-format)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "sa" 'calibredb-sort-by-author)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "sp" 'calibredb-sort-by-pubdate)
 (spacemacs/set-leader-keys-for-major-mode 'calibredb-search-mode "sf" 'calibredb-sort-by-language)


 (define-key evil-insert-state-map (kbd "S-RET") 'org-insert-todo-subheading)
 (define-key evil-insert-state-map (kbd "C-j") 'hippie-expand)

)


;; Do not write anything past this comment. This is where Emacs will
;; auto-generate custom variable definitions.
(defun dotspacemacs/emacs-custom-settings ()
  "Emacs custom settings.
This is an auto-generated function, do not modify its content directly, use
Emacs customize menu instead.
This function is called at the very end of Spacemacs initialization."
(custom-set-variables
 ;; custom-set-variables was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 '(deft-archive-directory "~/notes/archive")
 '(deft-directory "~/notes")
 '(deft-new-file-format "%Y-%m-%d-%H%M")
 '(deft-use-filename-as-title t)
 '(deft-use-filter-string-for-filename t)
 '(org-agenda-file-regexp "/notes/.*\\\\.org")
 '(org-agenda-files "~/notes")
 '(org-format-latex-options
   '(:foreground default :background default :scale 2.0 :html-foreground "Red" :html-background "Transparent" :html-scale 1.0 :matchers
                 ("begin" "$1" "$" "$$" "\\(" "\\[")))
 '(package-selected-packages
   '(openwith hledger-mode ox-hugo tomelr ox-gfm auto-dictionary flyspell-correct-helm flyspell-correct flycheck-plantuml bundler chruby minitest rake rbenv robe inf-ruby rspec-mode rubocop rubocopfmt ruby-hash-syntax ruby-refactor ruby-test-mode ruby-tools rvm seeing-is-believing chatgpt company-ledger helm-pass password-store-otp password-store ac-ispell afternoon-theme ahk-mode alect-themes ample-theme ample-zen-theme anti-zenburn-theme apropospriate-theme auto-complete auto-yasnippet badwolf-theme birds-of-paradise-plus-theme blacken browse-at-remote bubbleberry-theme busybee-theme calibredb ccls cherry-blossom-theme chocolate-theme cider-eval-sexp-fu clojure-snippets clues-theme code-cells color-theme-sanityinc-solarized color-theme-sanityinc-tomorrow common-lisp-snippets company-anaconda anaconda-mode company-auctex company-c-headers company-go company-math company-reftex company-rtags company-web web-completion-data company-ycmd cpp-auto-include cyberpunk-theme cython-mode dakrone-theme darkmine-theme darkokai-theme darktooth-theme disaster django-theme docker aio docker-tramp dockerfile-mode doom-themes dracula-theme ebib emmet-mode engine-mode esh-help eshell-prompt-extras eshell-z espresso-theme evil-ledger evil-org evil-tex exotica-theme eziam-themes farmhouse-themes flatland-theme flatui-theme flycheck-hledger flycheck-ledger flycheck-pos-tip pos-tip flycheck-rtags flycheck-ycmd fuzzy gandalf-theme geiser gendoxy gh-md git-gutter-fringe fringe-helper git-gutter git-link git-messenger git-modes git-timemachine gitignore-templates gnuplot go-eldoc go-fill-struct go-gen-test go-guru go-impl go-rename go-tag go-mode godoctor google-c-style gotham-theme grandshell-theme graphviz-dot-mode groovy-imports pcache groovy-mode gruber-darker-theme gruvbox-theme hc-zenburn-theme helm-bibtex helm-c-yasnippet helm-cider cider sesman parseedn clojure-mode parseclj helm-company helm-css-scss helm-git-grep helm-ls-git helm-lsp helm-org-rifle helm-pydoc helm-rtags helpful elisp-refs hemisu-theme heroku-theme ibuffer-projectile impatient-mode importmagic epc ctable concurrent inkpot-theme ir-black-theme jazz-theme jbeans-theme js-doc js2-refactor multiple-cursors json-mode json-navigator hierarchy json-reformat json-snatcher kaolin-themes ledger-import ledger-mode light-soap-theme live-py-mode livid-mode lsp-java dap-mode lsp-docker bui lsp-latex lsp-origami origami lsp-pyright lsp-python-ms lsp-treemacs lsp-ui lsp-mode lush-theme madhat2r-theme majapahit-theme markdown-toc material-theme math-symbol-lists maven-test-mode minimal-theme mmm-mode modus-themes moe-theme molokai-theme monochrome-theme monokai-theme multi-term multi-vterm xref mustang-theme mvn naquadah-theme noctilux-theme nodejs-repl nose nov esxml kv npm-mode ob-powershell obsidian-theme occidental-theme oldlace-theme omtose-phellack-theme org org-brain org-cliplink org-contacts org-contrib org-download org-mime org-pomodoro alert log4e gntp org-present org-projectile org-category-capture org-ref citeproc bibtex-completion htmlize biblio biblio-core parsebib org-rich-yank org-roam-ui websocket org-roam org-sticky-header org-vcard organic-green-theme orgit-forge orgit forge yaml markdown-mode ghub closql emacsql-sqlite emacsql treepy ox-pandoc pandoc-mode pdf-view-restore pdf-tools tablist phoenix-dark-mono-theme phoenix-dark-pink-theme pip-requirements pipenv load-env-vars pippel planet-theme plantuml-mode poetry prettier-js professional-theme pug-mode purple-haze-theme py-isort pydoc pyenv-mode pythonic pylookup pytest pyvenv railscasts-theme rebecca-theme reverse-theme rtags sass-mode haml-mode scss-mode seti-theme shell-pop sicp skewer-mode js2-mode simple-httpd slim-mode slime-company slime smeargle smyx-theme soft-charcoal-theme soft-morning-theme soft-stone-theme solarized-theme soothe-theme autothemer spacegray-theme sphinx-doc sql-indent subatomic-theme subatomic256-theme sublime-themes sunny-day-theme tagedit tango-2-theme tango-plus-theme tangotango-theme tao-theme terminal-here texfrag auctex tide toxi-theme treemacs-magit magit magit-section git-commit with-editor transient twilight-anti-bright-theme twilight-bright-theme twilight-theme typescript-mode ujelly-theme underwater-theme valign vterm web-beautify web-mode white-sand-theme xterm-color yapfify yasnippet-snippets yatemplate ycmd request-deferred deferred zen-and-art-theme zenburn-theme zetteldeft deft zonokai-emacs company-dcd yasnippet company counsel-gtags counsel swiper ivy d-mode flycheck-dmd-dub ggtags helm-gtags ace-jump-helm-line ace-link aggressive-indent auto-compile auto-highlight-symbol centered-cursor-mode clean-aindent-mode column-enforce-mode define-word devdocs dired-quick-sort drag-stuff dumb-jump editorconfig elisp-def elisp-slime-nav emr clang-format list-utils eval-sexp-fu evil-anzu anzu evil-args evil-cleverparens paredit evil-collection annalist evil-easymotion evil-escape evil-exchange evil-goggles evil-iedit-state iedit evil-indent-plus evil-lion evil-lisp-state evil-matchit evil-mc evil-nerd-commenter evil-numbers evil-surround evil-textobj-line evil-tutor evil-unimpaired evil-visual-mark-mode evil-visualstar expand-region eyebrowse fancy-battery flx-ido flx flycheck-elsa flycheck-package package-lint flycheck golden-ratio google-translate helm-ag helm-descbinds helm-make helm-mode-manager helm-org helm-projectile helm-purpose helm-swoop helm-themes helm-xref helm helm-core help-fns+ hide-comnt ws-butler writeroom-mode winum window-purpose which-key volatile-highlights vim-powerline vi-tilde-fringe uuidgen use-package undo-tree treemacs-projectile treemacs-persp treemacs-icons-dired treemacs-evil toc-org term-cursor symon symbol-overlay string-inflection string-edit-at-point spacemacs-whitespace-cleanup spacemacs-purpose-popwin spaceline-all-the-icons space-doc smartparens restart-emacs request rainbow-delimiters quickrun popwin popup pcre2el password-generator paradox overseer org-superstar open-junk-file nameless multi-line macrostep lorem-ipsum link-hint inspector info+ indent-guide hybrid-mode hungry-delete holy-mode hl-todo highlight-parentheses highlight-numbers highlight-indentation font-lock+ evil-evilified-state dotenv-mode diminish bind-map async)))
(custom-set-faces
 ;; custom-set-faces was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 '(bold ((t (:box (:line-width (2 . 2) :color "grey75" :style released-button) :weight bold))))
 '(bold-italic ((t (:box (:line-width (2 . 2) :color "grey75" :style released-button) :slant italic :weight bold))))
 '(highlight ((t (:background "#7c6f64" :foreground "#fdf4c1" :box nil))))
 '(italic ((t (:distant-foreground "dark green" :box (:line-width (2 . 2) :color "yellow4" :style released-button) :slant italic))))
 '(org-block-begin-line ((t (:extend t :background "#3c3836" :height 1.0))))
 '(org-block-end-line ((t (:extend t :background "#3c3836" :height 1.0))))
 '(org-checkbox ((t (:inherit default))))
 '(org-checkbox-statistics-done ((t (:inherit (default org-done) :strike-through t))))
 '(org-code ((t (:inherit shadow :box (:line-width (2 . 2) :color "dark red" :style released-button))))))
)
```

[file:\~/.spacemacs::;; -\*- mode: emacs-lisp; lexical-binding: t -\*-](~/.spacemacs::;; -*- mode: emacs-lisp; lexical-binding: t -*-)

``` {#프로젝트 레이어 목표 .dired}
drwxr-xr-x  6 june june   4096 Feb 19 14:07   +chat
drwxr-xr-x  4 june june   4096 Feb 19 14:07   +checkers
drwxr-xr-x  7 june june   4096 Feb 19 14:07   +completion
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +distributions
drwxr-xr-x 11 june june   4096 Feb 19 14:07   +emacs
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +email
drwxr-xr-x  4 june june   4096 Feb 19 14:07   +filetree
drwxr-xr-x  3 june june   4096 Feb 19 14:07   +fonts
drwxr-xr-x  9 june june   4096 Feb 19 14:07   +frameworks
drwxr-xr-x  6 june june   4096 Feb 19 14:07   +fun
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +intl
drwxr-xr-x 83 june june   4096 Feb 19 14:07   +lang
drwxr-xr-x  8 june june   4096 Feb 19 14:07   +misc
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +music
drwxr-xr-x  4 june june   4096 Feb 19 14:07   +os
drwxr-xr-x  3 june june   4096 Feb 19 14:07   +pair-programming
drwxr-xr-x  9 june june   4096 Feb 19 14:07   +readers
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +source-control
drwxr-xr-x 16 june june   4096 Feb 19 14:07   +spacemacs
drwxr-xr-x  4 june june   4096 Feb 19 14:07   +tags
drwxr-xr-x  5 june june   4096 Feb 19 14:07   +themes
drwxr-xr-x 52 june june   4096 Feb 19 14:07   +tools
drwxr-xr-x  7 june june   4096 Feb 19 14:07   +vim
drwxr-xr-x  3 june june   4096 Feb 19 14:07   +web
drwxr-xr-x 13 june june   4096 Feb 19 14:07   +web-services
drwxr-xr-x  3 june june   4096 Feb 19 14:07   +window-management
```

[file:\~/.emacs.d/layers/+window-management](~/.emacs.d/layers/+window-management)

## 프로젝트B

### 프로젝트 개요

개인 지식 관리 프로젝트의 목표는 지식을 때에 맞게 회수하는 것에 대한
중요성과 함께 시작되었습니다 개인 지식 관리 프로젝트는 Emacs를 제가
지식과 정보를 효과적으로 관리하는 것을 목표로 합니다. 이 프로젝트의
목표는 제가 이전보다 더 빠르게 필요한 정보를 검색하고, 제 아이디어와
생각을 보다 쉽게 기록하고, 관리할 수 있도록 돕는 것입니다.

### 프로젝트 목표

-   인공지능에 의한 인류의 멸망을 방지하기 위해 노력

### 프로젝트 범위

-   Emacs 기능을 활용하여 지식 관리 도구 제작
-   사용자 지식 관리 설정 파일 \"\~/notes\" 관리
-   Git를 이용한 \"\~/note\" 버전관리

### 프로젝트 일정

-   문서 작성 및 업데이트: 주1회

### 프로젝트 예산

개인 지식 관리 프로젝트의 예산은 다음과 같습니다:

-   개발자 1명: 나 자신
-   개발 도구 및 서버 비용: 무

### 프로젝트 위험 관리

개인 지식 관리 프로젝트의 위험 요소와 관리 방안은 다음과 같습니다:

-   삭제 방지
-   컴퓨터 저장공간 확충을 위한 pcloud 클라우드 저장 공간 도입
-   개념을 이용하여 지식을 구분한 것이 아닌 인물로 지식 구분 진행

### 프로젝트 진행 상황

``` {#프로젝트 파일 .dired}
drwxr-xr-x   2 june june     4096 Feb 26 05:38   Abraham Maslow
drwxr-xr-x   2 june june     4096 Feb 25 06:22   Adam Smith
drwxr-xr-x   2 june june     4096 Feb 23 20:03   Adolf Hitler
drwxr-xr-x   2 june june     4096 Feb 27 14:03   Albert Einstein
drwxr-xr-x   2 june june     4096 Feb 26 23:44   Allan Turing
drwxr-xr-x   2 june june     4096 Feb 24 20:41   Ana Bell
drwxr-xr-x   2 june june     4096 Feb 23 20:20   Aristotle
drwxr-xr-x   2 june june     4096 Feb 26 22:38   Arthur Schopenhauer
drwxr-xr-x   2 june june     4096 Feb 23 20:40   Baruch Spinoza
drwxr-xr-x   2 june june     4096 Feb 23 20:22   Benjamin Franklin
drwxr-xr-x   3 june june     4096 Feb 27 12:05   Bertrand Russell
drwxr-xr-x   2 june june     4096 Feb 23 20:26   Bill Gates
drwxr-xr-x   2 june june     4096 Feb 23 20:07   Bjarne Stroustrup
drwxr-xr-x   2 june june     4096 Feb 23 23:45   Bram Moolenaar
drwxr-xr-x   2 june june     4096 Feb 23 20:31   Carl Jung
drwxr-xr-x   2 june june     4096 Feb 25 21:26   Carsten Dominik
drwxr-xr-x   3 june june     4096 Feb 26 04:16   Claude Shannon
drwxr-xr-x   2 june june     4096 Feb 23 20:28   Dante
drwxr-xr-x   2 june june     4096 Feb 25 07:24   Dave Ramsey
drwxr-xr-x   2 june june     4096 Feb 24 21:03   David Allen
drwxr-xr-x   2 june june     4096 Feb 24 19:18   David Hume
drwxr-xr-x   2 june june     4096 Feb 24 20:49   David J. Malan
drwxr-xr-x   2 june june     4096 Feb 23 20:07   Dennis Ritchie
drwxr-xr-x   2 june june     4096 Feb 25 04:03   Donald Knuth
drwxr-xr-x   2 june june    12288 Feb 26 20:35   downloads
drwxr-xr-x   2 june june     4096 Feb 23 20:00   Elon Musk
drwxr-xr-x   2 june june     4096 Feb 23 20:17   Erwin Schrodinger
drwxr-xr-x   2 june june     4096 Feb 24 03:54   Euclid
drwxr-xr-x   2 june june     4096 Feb 23 20:04   Friedrich Nietzsche
drwxr-xr-x   2 june june     4096 Feb 23 20:20   Galileo Galilei
drwxr-xr-x   2 june june     4096 Feb 25 20:31   Garry McKinnon
drwxr-xr-x   2 june june     4096 Feb 24 05:36   Gilbert Strang
drwxr-xr-x   7 june june     4096 Feb 26 23:45   .git
drwxr-xr-x   3 june june     4096 Feb 25 04:33   Github Repository
drwxr-xr-x   2 june june     4096 Feb 26 04:16   Gottfried Leibniz
drwxr-xr-x   2 june june     4096 Feb 23 20:14   Gottlob Frege
drwxr-xr-x   2 june june     4096 Feb 23 22:21   Guido van Rossum
drwxr-xr-x   2 june june     4096 Feb 23 20:23   Harold Abelson
drwxr-xr-x   2 june june     4096 Feb 23 20:29   Hegel
drwxr-xr-x   2 june june     4096 Feb 26 04:25   Hippaarchus
-rw-r--r--   1 june june 47871417 Feb 28 04:09   How to Read a Book_ The classic guide to intelligent reading ( PDFDrive ).pdf
-rw-r--r--   1 june june      258 Feb 28 04:09   How to Read a Book_ The classic guide to intelligent reading ( PDFDrive ).pdf:Zone.Identifier
drwxr-xr-x   2 june june     4096 Feb 25 17:44   image
drwxr-xr-x   2 june june     4096 Feb 25 17:41   Immanuel Kant
drwxr-xr-x   2 june june     4096 Feb 23 20:19   Isaac Newton
drwxr-xr-x   2 june june     4096 Feb 23 20:20   James Clerk Maxwell
drwxr-xr-x   2 june june     4096 Feb 23 20:24   James Gosling
drwxr-xr-x   2 june june     4096 Feb 23 23:14   James Hutton
drwxr-xr-x   2 june june     4096 Feb 23 20:54   Jane Goodall
drwxr-xr-x   2 june june     4096 Feb 23 20:15   Jean-Jacques Rousseau
drwxr-xr-x   2 june june     4096 Feb 24 02:20   Jeffrey Friedl
drwxr-xr-x   2 june june     4096 Feb 23 20:26   John Backus
drwxr-xr-x   2 june june     4096 Feb 25 20:26   John Carmack
drwxr-xr-x   2 june june     4096 Feb 23 20:16   John Locke
drwxr-xr-x   2 june june     4096 Feb 26 23:19   John McCarthy
drwxr-xr-x   2 june june     4096 Feb 23 20:40   John Stuwart Mill
drwxr-xr-x   2 june june     4096 Feb 24 02:20   John Von Neumann
drwxr-xr-x   2 june june     4096 Feb 25 16:23   John Warmock
drwxr-xr-x   2 june june     4096 Feb 26 01:01   Jordan Peterson
drwxr-xr-x   2 june june     4096 Feb 23 20:03   Joseph Stalin
drwxr-xr-x   2 june june     4096 Feb 23 20:17   J. Robert Oppenheimer
drwxr-xr-x   2 june june     4096 Feb 23 20:27   Karl Marx
drwxr-xr-x   2 june june     4096 Feb 23 20:26   Ken Thompson
drwxr-xr-x   2 june june     4096 Feb 23 20:19   Kurt Godel
drwxr-xr-x   2 june june     4096 Feb 23 20:16   Leo Tolstoy
drwxr-xr-x   2 june june     4096 Feb 26 01:28   Lex Fridman
drwxr-xr-x   2 june june     4096 Feb 26 01:37   libraries
drwxr-xr-x   3 june june     4096 Feb 25 03:20   link
drwxr-xr-x   2 june june     4096 Feb 25 05:46   Linus Torvalds
drwxr-xr-x   2 june june     4096 Feb 23 20:18   Ludwig Boltzmann
drwxr-xr-x   2 june june     4096 Feb 23 21:43   Ludwig Wittgenstein
drwxr-xr-x   2 june june     4096 Feb 25 04:07   Micahel linenberger
drwxr-xr-x   2 june june     4096 Feb 23 20:30   Michael Foucault
drwxr-xr-x   2 june june     4096 Feb 26 04:01   Mike Girvin
drwxr-xr-x   2 june june     4096 Feb 23 20:39   Muhammad ibn Musa al-Khwarizmi
drwxr-xr-x   2 june june     4096 Feb 28 14:46   Nick Bostrom
drwxr-xr-x   2 june june     4096 Feb 27 16:47   Nicole van der Hoeven
drwxr-xr-x   2 june june     4096 Feb 23 20:25   Nikaus Wirth
drwxr-xr-x   2 june june     4096 Feb 23 23:23   Nikola Tesla
drwxr-xr-x   2 june june     4096 Feb 23 20:15   Plato
drwxr-xr-x   2 june june     4096 Feb 28 17:17   project
drwxr-xr-x   2 june june     4096 Feb 24 20:58   Ray Dalio
drwxr-xr-x   3 june june     4096 Feb 27 12:17   Ray Kurzweil
drwxr-xr-x   3 june june     4096 Feb 24 19:56   Rene Descarte
drwxr-xr-x   3 june june     4096 Feb 27 13:02   Richard Feynman
drwxr-xr-x   2 june june     4096 Feb 28 14:46   Richard Stallman
drwxr-xr-x   2 june june     4096 Feb 26 05:38   Roger Tomlinson
drwxr-xr-x   2 june june     4096 Feb 24 20:37   Satya Nadella
drwxr-xr-x   2 june june     4096 Feb 23 20:28   Socrates
drwxr-xr-x   2 june june     4096 Feb 23 20:29   Soren Kierkegaard
drwxr-xr-x   2 june june     4096 Feb 23 20:05   Stephen Bourne
drwxr-xr-x   2 june june     4096 Feb 23 20:08   Steve Jobs
drwxr-xr-x   2 june june     4096 Feb 23 23:26   Sylvain Benner
drwxr-xr-x   2 june june     4096 Feb 24 02:20   Terence Tao
drwxr-xr-x   2 june june     4096 Feb 23 20:22   Thomas Edison
drwxr-xr-x   2 june june     4096 Feb 23 20:27   Tim Berners Lee
drwxr-xr-x   2 june june     4096 Feb 25 04:41   Tom Preston-Werner
drwxr-xr-x   2 june june     4096 Feb 24 20:39   Travis Oliphant
drwxr-xr-x   2 june june     4096 Feb 23 20:16   Voltaire
drwxr-xr-x   2 june june     4096 Feb 23 20:13   Warren Buffet
```

[file:\~/notes/](~/notes/)

``` {#개인 인물별 빠른 이동 관리 .lisp-data}
;;;; Emacs Bookmark Format Version 1;;;; -*- coding: utf-8-emacs; mode: lisp-data -*-
;;; This format is meant to be slightly human-readable;
;;; nevertheless, you probably don't want to edit it.
;;; -*- End Of Bookmark File Format Version Stamp -*-
(("51) people"
 (filename . "~/notes/")
 (front-context-string . "Adam Smith\n  drw")
 (rear-context-string . " Feb 25 06:22   ")
 (position . 404))
("50) Albert Einstein"
 (filename . "~/notes/Albert Einstein/AlbertEinstein.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("49) Einstein"
 (filename . "~/notes/Richard Feynman/RichardFeynman.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("48) Bertrand Russell"
 (filename . "~/notes/Bertrand Russell/BertrandRussell.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("47) Claude Shannon"
 (filename . "~/notes/Claude Shannon/ClaudeShannon.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("46) Mike Girvin"
 (filename . "~/notes/Mike Girvin/MikeGirvin.org")
 (front-context-string . "[[~/notes/downlo")
 (rear-context-string)
 (position . 1))
("45) Ray Kurzeil"
 (filename . "~/notes/Ray Kurzweil/RayKurzweil.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("44) Downloads"
 (filename . "~/notes/downloads/")
 (front-context-string . "The Singularity ")
 (rear-context-string . " Feb 26 01:29   ")
 (position . 348))
("figure 2.1 VisiCalc, the first spreadsheet tool, was invented by Dan Bricklin(left) and Bob Frankston"
 (filename . "~/notes/Mike Girvin/Microsoft 365 Excel The Only Ap - Mike Girvin.pdf")
 (position . 1)
 (page . 36)
 (slice)
 (size . fit-width)
 (origin 0.0 . 0.0)
 (handler . pdf-view-bookmark-jump-handler))
("43) John Warmock"
 (filename . "~/notes/John Warmock/JohnWarmock.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("42) Linus Torvald"
 (filename . "~/notes/Linus Torvalds/LinusTorvalds.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("41) Github Repository"
 (filename . "~/notes/Github Repository/")
 (front-context-string)
 (rear-context-string . "25 04:33   .git\n")
 (position . 237))
("40) Tom Preston Werner"
 (filename . "~/notes/Tom Preston-Werner/TomPrestonWerner.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("39) Michael Linenberger"
 (filename . "~/notes/Micahel linenberger/MichaelLinenberger.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("39) Donald Knuth"
 (filename . "~/notes/Donald Knuth/DonaldKnuth.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("38) David Allen"
 (filename . "~/notes/David Allen/DavidAllen.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("37) David Malan"
 (filename . "~/notes/David J. Malan/DavidJ.Malan.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("36) Satya Nadella"
 (filename . "~/notes/Satya Nadella/SatyaNadella.org")
 (front-context-string . "* from no on you")
 (rear-context-string)
 (position . 1))
("35) David Hume"
 (filename . "~/notes/David Hume/DavidHume.org")
 (front-context-string)
 (rear-context-string)
 (position . 1))
("34) Gilbert Strang"
 (filename . "~/notes/Gilbert Strang/GilbertStrang.org")
 (front-context-string)
 (rear-context-string)
 (position . 1))
("33) Mark Girvin"
 (filename . "~/notes/Mark Girvin/MarkGirvin.org")
 (front-context-string)
 (rear-context-string)
 (position . 1))
("32) Hippaarchus"
 (filename . "~/notes/Hippaarchus/Hippaarchus.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("31) Gottfried Leibnitz"
 (filename . "~/notes/Gottfried Leibniz/GottfriedLeibnitz.org")
 (front-context-string . "z\nGreetings! I a")
 (rear-context-string . "ottfried Leibnit")
 (position . 67))
("30) Ana Bell"
 (filename . "~/notes/Ana Bell/AnaBell.org")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("29) Carsten Dominik"
 (filename . "~/notes/Carsten Dominik/CarstenDominik.org")
 (front-context-string)
 (rear-context-string . "e Carsten Domini")
 (position . 64))
("28) Nikola Tesla Engineer"
 (filename . "~/dialog/Nikola Tesla")
 (front-context-string . "* from now on yo")
 (rear-context-string)
 (position . 1))
("27) James Hutton Geology"
 (filename . "~/dialog/James Hutton/JamesHutton.org")
 (front-context-string . "#+TITLE: James H")
 (rear-context-string)
 (position . 1))
("26) Guido Von Rossum"
 (filename . "~/dialog/Guido van Rossum/")
 (front-context-string . "#TITLE: Guido Vo")
 (rear-context-string)
 (position . 1))
("25) Jeffrey Friedl"
 (filename . "~/dialog/Jeffrey Friedl/JeffreyFriedl.org")
 (front-context-string . "from now on you ")
 (rear-context-string)
 (position . 3))
("24) Ludwig Wittgenstein"
 (filename . "~/dialog/Ludwig Wittgenstein/LudwigWittgenstein.org")
 (front-context-string . "n\nAs Ludwig Witt")
 (rear-context-string . "dwig Wittgenstei")
 (position . 68))
("23) AllanTuring.org"
 (filename . "~/dialog/Allan Turing/")
 (front-context-string)
 (rear-context-string . "b 23 20:54   ..\n")
 (position . 183))
("22) Satya Nadella"
 (filename . "~/dialog/Satya Nadella/")
 (front-context-string . "* from no on you")
 (rear-context-string)
 (position . 1))
("21) Richard Stallman"
 (filename . "~/notes/Richard Stallman/RichardStallman.org")
 (front-context-string . "#TITLE: Richard ")
 (rear-context-string)
 (position . 1))
("20) Janes Goodall"
 (filename . "~/dialog/Jane Goodall/JaneGoodall.org")
 (front-context-string . "\n* act as if you")
 (rear-context-string . ": Janes Goodall\n")
 (position . 23))
("19)plantuml layer"
 (filename . "~/.emacs.d/layers/+lang/plantuml/README.org")
 (front-context-string . "Install\nTo use t")
 (rear-context-string . "y from emacs\n\n* ")
 (position . 1755))
("org-capture-last-stored"
 (filename . "~/notes/link/20230224023539-not.org")
 (front-context-string)
 (rear-context-string . "D:\n#+title: not\n")
 (position . 81))
("18) notes"
 (filename . "~/.spacemacs.d/notes/")
 (front-context-string . "05.org\n  drwxr-x")
 (rear-context-string . " Feb 21 06:20   ")
 (position . 558))
("17) june"
 (filename . "~/")
 (front-context-string . ".spacemacs.d\n  -")
 (rear-context-string . " Feb 19 16:26   ")
 (position . 597))
("16) downloa"
 (filename . "/mnt/c/Users/JH_Ju/Downloads/")
 (front-context-string . "~$crosoft 365 Ex")
 (rear-context-string . " Feb  6 06:52   ")
 (position . 237))
("15) documents"
 (filename . "/mnt/c/Users/JH_Ju/Documents/")
 (front-context-string . ".git\n  drwxrwxrw")
 (rear-context-string . " Feb 17 10:39   ")
 (position . 230))
("14) jh_june"
 (filename . "/mnt/c/Users/JH_Ju/")
 (front-context-string . "Documents\n  drwx")
 (rear-context-string . " Feb 20 02:03   ")
 (position . 1176))
("13) c"
 (filename . "/mnt/c/")
 (front-context-string . "Program Files\n  ")
 (rear-context-string . "96 Feb 20 01:37 ")
 (position . 918))
("12) root"
 (filename . "/")
 (front-context-string . "mnt\n  drwxr-xr-x")
 (rear-context-string . " Jan 27 20:45   ")
 (position . 804))
("11) etc"
 (filename . "/etc/")
 (front-context-string . "locale.gen\n  lrw")
 (rear-context-string . " Jan 27 21:34   ")
 (position . 3048))
("10) snippets"
 (filename . "~/.spacemacs.d/snippets/org-mode/")
 (front-context-string . "6*\n  -rw-r--r-- ")
 (rear-context-string . " Feb 19 19:38   ")
 (position . 283))
("9) mainnotes"
 (filename . "~/.spacemacs.d/notes/mainnotes.org")
 (front-context-string . " task\n* manage\n*")
 (rear-context-string)
 (position . 2))
("8) learn python 3 the hard way"
 (filename . "~/.spacemacs.d/notes/mainnotes.org")
 (front-context-string . "keep track of al")
 (rear-context-string . "\n**** how can I ")
 (position . 94))
("7) helm bookmarks"
 (filename . "~/.emacs.d/.cache/bookmarks")
 (front-context-string . "((\"4) spacemacs ")
 (rear-context-string . "rsion Stamp -*-\n")
 (position . 251))
("4) spacemacs dotfile user-config"
 (filename . "~/.spacemacs")
 (front-context-string . "(defun dotspacem")
 (rear-context-string . " the\ndump.\"\n)\n\n\n")
 (position . 29057))
("5) spacemacs dotfile configuration-layer"
 (filename . "~/.spacemacs")
 (front-context-string . "   dotspacemacs-")
 (rear-context-string . "layers to load.\n")
 (position . 1311))
("3) ~"
 (filename . "~/")
 (front-context-string . ".spacemacs.d\n  -")
 (rear-context-string . " Feb 19 16:26   ")
 (position . 776))
("2) external"
 (filename . "~/.spacemacs.d/notes/external/")
 (front-context-string . "..\n  -rw-r--r-- ")
 (rear-context-string . " Feb 19 16:48   ")
 (position . 198))
("1) converts"
 (filename . "~/.spacemacs.d/notes/converts/")
 (front-context-string . "Learn Python 3 T")
 (rear-context-string . " Feb 19 16:19   ")
 (position . 472))
("6) spacemacs dotfile bookmarks org-capture-last-stored"
 (filename . "~/.spacemacs.d/notes/20230219163229-.org")
 (front-context-string)
 (rear-context-string . "END:\n#+title: -\n")
 (position . 79))
)
```

[file:\~/.emacs.d/.cache/bookmarks::;;;; Emacs Bookmark Format Version 1;;;; -\*- coding: utf-8-emacs; mode: lisp-data -\*-](~/.emacs.d/.cache/bookmarks::;;;; Emacs Bookmark Format Version 1;;;; -*- coding: utf-8-emacs; mode: lisp-data -*-)

# 프로젝트A Spacemacs 프로젝트
## 폴더 
- drwxr-xr-x  6 june june   4096 Feb 19 14:07   +chat
- drwxr-xr-x  4 june june   4096 Feb 19 14:07   +checkers
- drwxr-xr-x  7 june june   4096 Feb 19 14:07   +completion
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +distributions
- drwxr-xr-x 11 june june   4096 Feb 19 14:07   +emacs
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +email
- drwxr-xr-x  4 june june   4096 Feb 19 14:07   +filetree
- drwxr-xr-x  3 june june   4096 Feb 19 14:07   +fonts
- drwxr-xr-x  9 june june   4096 Feb 19 14:07   +frameworks
- drwxr-xr-x  6 june june   4096 Feb 19 14:07   +fun
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +intl
- drwxr-xr-x 83 june june   4096 Feb 19 14:07   +lang
- drwxr-xr-x  8 june june   4096 Feb 19 14:07   +misc
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +music
- drwxr-xr-x  4 june june   4096 Feb 19 14:07   +os
- drwxr-xr-x  3 june june   4096 Feb 19 14:07   +pair-programming
- drwxr-xr-x  9 june june   4096 Feb 19 14:07   +readers
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +source-control
- drwxr-xr-x 16 june june   4096 Feb 19 14:07   +spacemacs
- drwxr-xr-x  4 june june   4096 Feb 19 14:07   +tags
- drwxr-xr-x  5 june june   4096 Feb 19 14:07   +themes
- drwxr-xr-x 52 june june   4096 Feb 19 14:07   +tools
- drwxr-xr-x  7 june june   4096 Feb 19 14:07   +vim
- drwxr-xr-x  3 june june   4096 Feb 19 14:07   +web
- drwxr-xr-x 13 june june   4096 Feb 19 14:07   +web-services
- drwxr-xr-x  3 june june   4096 Feb 19 14:07   +window-management

# 프로젝트B 지식관리
## 폴더
- drwxr-xr-x   2 june june     4096 Feb 26 05:38   Abraham Maslow
- drwxr-xr-x   2 june june     4096 Feb 25 06:22   Adam Smith
- drwxr-xr-x   2 june june     4096 Feb 23 20:03   Adolf Hitler
- drwxr-xr-x   2 june june     4096 Feb 27 14:03   Albert Einstein
- drwxr-xr-x   2 june june     4096 Feb 26 23:44   Allan Turing
- drwxr-xr-x   2 june june     4096 Feb 24 20:41   Ana Bell
- drwxr-xr-x   2 june june     4096 Feb 23 20:20   Aristotle
- drwxr-xr-x   2 june june     4096 Feb 26 22:38   Arthur Schopenhauer
- drwxr-xr-x   2 june june     4096 Feb 23 20:40   Baruch Spinoza
- drwxr-xr-x   2 june june     4096 Feb 23 20:22   Benjamin Franklin
- drwxr-xr-x   3 june june     4096 Feb 27 12:05   Bertrand Russell
- drwxr-xr-x   2 june june     4096 Feb 23 20:26   Bill Gates
- drwxr-xr-x   2 june june     4096 Feb 23 20:07   Bjarne Stroustrup
- drwxr-xr-x   2 june june     4096 Feb 23 23:45   Bram Moolenaar
- drwxr-xr-x   2 june june     4096 Feb 23 20:31   Carl Jung
- drwxr-xr-x   2 june june     4096 Feb 25 21:26   Carsten Dominik
- drwxr-xr-x   3 june june     4096 Feb 26 04:16   Claude Shannon
- drwxr-xr-x   2 june june     4096 Feb 23 20:28   Dante
- drwxr-xr-x   2 june june     4096 Feb 25 07:24   Dave Ramsey
- drwxr-xr-x   2 june june     4096 Feb 24 21:03   David Allen
- drwxr-xr-x   2 june june     4096 Feb 24 19:18   David Hume
- drwxr-xr-x   2 june june     4096 Feb 24 20:49   David J. Malan
- drwxr-xr-x   2 june june     4096 Feb 23 20:07   Dennis Ritchie
- drwxr-xr-x   2 june june     4096 Feb 25 04:03   Donald Knuth
- drwxr-xr-x   2 june june    12288 Feb 26 20:35   downloads
- drwxr-xr-x   2 june june     4096 Feb 23 20:00   Elon Musk
- drwxr-xr-x   2 june june     4096 Feb 23 20:17   Erwin Schrodinger
- drwxr-xr-x   2 june june     4096 Feb 24 03:54   Euclid
- drwxr-xr-x   2 june june     4096 Feb 23 20:04   Friedrich Nietzsche
- drwxr-xr-x   2 june june     4096 Feb 23 20:20   Galileo Galilei
- drwxr-xr-x   2 june june     4096 Feb 25 20:31   Garry McKinnon
- drwxr-xr-x   2 june june     4096 Feb 24 05:36   Gilbert Strang
- drwxr-xr-x   7 june june     4096 Feb 26 23:45   .git
- drwxr-xr-x   3 june june     4096 Feb 25 04:33   Github Repository
- drwxr-xr-x   2 june june     4096 Feb 26 04:16   Gottfried Leibniz
- drwxr-xr-x   2 june june     4096 Feb 23 20:14   Gottlob Frege
- drwxr-xr-x   2 june june     4096 Feb 23 22:21   Guido van Rossum
- drwxr-xr-x   2 june june     4096 Feb 23 20:23   Harold Abelson
- drwxr-xr-x   2 june june     4096 Feb 23 20:29   Hegel
- drwxr-xr-x   2 june june     4096 Feb 26 04:25   Hippaarchus
- drwxr-xr-x   2 june june     4096 Feb 25 17:44   image
- drwxr-xr-x   2 june june     4096 Feb 25 17:41   Immanuel Kant
- drwxr-xr-x   2 june june     4096 Feb 23 20:19   Isaac Newton
- drwxr-xr-x   2 june june     4096 Feb 23 20:20   James Clerk Maxwell
- drwxr-xr-x   2 june june     4096 Feb 23 20:24   James Gosling
- drwxr-xr-x   2 june june     4096 Feb 23 23:14   James Hutton
- drwxr-xr-x   2 june june     4096 Feb 23 20:54   Jane Goodall
- drwxr-xr-x   2 june june     4096 Feb 23 20:15   Jean-Jacques Rousseau
- drwxr-xr-x   2 june june     4096 Feb 24 02:20   Jeffrey Friedl
- drwxr-xr-x   2 june june     4096 Feb 23 20:26   John Backus
- drwxr-xr-x   2 june june     4096 Feb 25 20:26   John Carmack
- drwxr-xr-x   2 june june     4096 Feb 23 20:16   John Locke
- drwxr-xr-x   2 june june     4096 Feb 26 23:19   John McCarthy
- drwxr-xr-x   2 june june     4096 Feb 23 20:40   John Stuwart Mill
- drwxr-xr-x   2 june june     4096 Feb 24 02:20   John Von Neumann
- drwxr-xr-x   2 june june     4096 Feb 25 16:23   John Warmock
- drwxr-xr-x   2 june june     4096 Feb 26 01:01   Jordan Peterson
- drwxr-xr-x   2 june june     4096 Feb 23 20:03   Joseph Stalin
- drwxr-xr-x   2 june june     4096 Feb 23 20:17   J. Robert Oppenheimer
- drwxr-xr-x   2 june june     4096 Feb 23 20:27   Karl Marx
- drwxr-xr-x   2 june june     4096 Feb 23 20:26   Ken Thompson
- drwxr-xr-x   2 june june     4096 Feb 23 20:19   Kurt Godel
- drwxr-xr-x   2 june june     4096 Feb 23 20:16   Leo Tolstoy
- drwxr-xr-x   2 june june     4096 Feb 26 01:28   Lex Fridman
- drwxr-xr-x   2 june june     4096 Feb 26 01:37   libraries
- drwxr-xr-x   3 june june     4096 Feb 25 03:20   link
- drwxr-xr-x   2 june june     4096 Feb 25 05:46   Linus Torvalds
- drwxr-xr-x   2 june june     4096 Feb 23 20:18   Ludwig Boltzmann
- drwxr-xr-x   2 june june     4096 Feb 23 21:43   Ludwig Wittgenstein
- drwxr-xr-x   2 june june     4096 Feb 25 04:07   Micahel linenberger
- drwxr-xr-x   2 june june     4096 Feb 23 20:30   Michael Foucault
- drwxr-xr-x   2 june june     4096 Feb 26 04:01   Mike Girvin
- drwxr-xr-x   2 june june     4096 Feb 23 20:39   Muhammad ibn Musa al-Khwarizmi
- drwxr-xr-x   2 june june     4096 Feb 28 14:46   Nick Bostrom
- drwxr-xr-x   2 june june     4096 Feb 27 16:47   Nicole van der Hoeven
- drwxr-xr-x   2 june june     4096 Feb 23 20:25   Nikaus Wirth
- drwxr-xr-x   2 june june     4096 Feb 23 23:23   Nikola Tesla
- drwxr-xr-x   2 june june     4096 Feb 23 20:15   Plato
- drwxr-xr-x   2 june june     4096 Feb 28 17:17   project
- drwxr-xr-x   2 june june     4096 Feb 24 20:58   Ray Dalio
- drwxr-xr-x   3 june june     4096 Feb 27 12:17   Ray Kurzweil
- drwxr-xr-x   3 june june     4096 Feb 24 19:56   Rene Descarte
- drwxr-xr-x   3 june june     4096 Feb 27 13:02   Richard Feynman
- drwxr-xr-x   2 june june     4096 Feb 28 14:46   Richard Stallman
- drwxr-xr-x   2 june june     4096 Feb 26 05:38   Roger Tomlinson
- drwxr-xr-x   2 june june     4096 Feb 24 20:37   Satya Nadella
- drwxr-xr-x   2 june june     4096 Feb 23 20:28   Socrates
- drwxr-xr-x   2 june june     4096 Feb 23 20:29   Soren Kierkegaard
- drwxr-xr-x   2 june june     4096 Feb 23 20:05   Stephen Bourne
- drwxr-xr-x   2 june june     4096 Feb 23 20:08   Steve Jobs
- drwxr-xr-x   2 june june     4096 Feb 23 23:26   Sylvain Benner
- drwxr-xr-x   2 june june     4096 Feb 24 02:20   Terence Tao
- drwxr-xr-x   2 june june     4096 Feb 23 20:22   Thomas Edison
- drwxr-xr-x   2 june june     4096 Feb 23 20:27   Tim Berners Lee
- drwxr-xr-x   2 june june     4096 Feb 25 04:41   Tom Preston-Werner
- drwxr-xr-x   2 june june     4096 Feb 24 20:39   Travis Oliphant
- drwxr-xr-x   2 june june     4096 Feb 23 20:16   Voltaire
- drwxr-xr-x   2 june june     4096 Feb 23 20:13   Warren Buffet
