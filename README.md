- Установка Java

    brew tap adoptopenjdk/openjdk
    brew install --cask adoptopenjdk8
    brew install --cask adoptopenjdk11

- проверка установленной версии

    /usr/libexec/java_home -V

- настройка JAVA_HOME

    echo 'export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)' >> ~/.zprofile
