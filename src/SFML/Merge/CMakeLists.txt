
#add_subdirectory(System)
#add_subdirectory(Window)
#add_subdirectory(Network)
#add_subdirectory(Graphics)
#add_subdirectory(Audio)

set(INCROOT ${CMAKE_SOURCE_DIR}/include/SFML/System)
set(SRCROOT ${CMAKE_SOURCE_DIR}/src/SFML/System)

# all source files
LIST(APPEND SRC 
	${INCROOT}/Export.h
    ${SRCROOT}/Clock.cpp
    ${SRCROOT}/ClockStruct.h
    ${INCROOT}/Clock.h
    ${INCROOT}/InputStream.h
    ${SRCROOT}/Mutex.cpp
    ${SRCROOT}/MutexStruct.h
    ${INCROOT}/Mutex.h
    ${SRCROOT}/Sleep.cpp
    ${INCROOT}/Sleep.h
    ${SRCROOT}/Thread.cpp
    ${SRCROOT}/ThreadStruct.h
    ${INCROOT}/Thread.h
    ${SRCROOT}/Time.cpp
    ${INCROOT}/Time.h
    ${INCROOT}/Types.h
    ${INCROOT}/Vector2.h
    ${INCROOT}/Vector3.h
)

set(INCROOT ${CMAKE_SOURCE_DIR}/include/SFML/Window)
set(SRCROOT ${CMAKE_SOURCE_DIR}/src/SFML/Window)

LIST(APPEND SRC 
    ${INCROOT}/Export.h
    ${SRCROOT}/Context.cpp
    ${SRCROOT}/ContextStruct.h
    ${INCROOT}/Context.h
    ${INCROOT}/Event.h
    ${SRCROOT}/Joystick.cpp
    ${INCROOT}/Joystick.h
    ${INCROOT}/JoystickIdentification.h
    ${SRCROOT}/Keyboard.cpp
    ${INCROOT}/Keyboard.h
    ${SRCROOT}/Mouse.cpp
    ${INCROOT}/Mouse.h
    ${SRCROOT}/Sensor.cpp
    ${INCROOT}/Sensor.h
    ${SRCROOT}/Touch.cpp
    ${INCROOT}/Touch.h
    ${INCROOT}/Types.h
    ${SRCROOT}/VideoMode.cpp
    ${INCROOT}/VideoMode.h
    ${SRCROOT}/Window.cpp
    ${SRCROOT}/WindowStruct.h
    ${INCROOT}/Window.h
    ${INCROOT}/WindowHandle.h
)

set(INCROOT ${CMAKE_SOURCE_DIR}/include/SFML/Network)
set(SRCROOT ${CMAKE_SOURCE_DIR}/src/SFML/Network)

LIST(APPEND SRC 
    ${INCROOT}/Export.h
    ${SRCROOT}/Ftp.cpp
    ${SRCROOT}/FtpStruct.h
    ${INCROOT}/Ftp.h
    ${SRCROOT}/Http.cpp
    ${SRCROOT}/HttpStruct.h
    ${INCROOT}/Http.h
    ${SRCROOT}/IpAddress.cpp
    ${INCROOT}/IpAddress.h
    ${SRCROOT}/Packet.cpp
    ${SRCROOT}/PacketStruct.h
    ${INCROOT}/Packet.h
    ${SRCROOT}/SocketSelector.cpp
    ${SRCROOT}/SocketSelectorStruct.h
    ${INCROOT}/SocketSelector.h
    ${INCROOT}/SocketStatus.h
    ${SRCROOT}/TcpListener.cpp
    ${SRCROOT}/TcpListenerStruct.h
    ${INCROOT}/TcpListener.h
    ${SRCROOT}/TcpSocket.cpp
    ${SRCROOT}/TcpSocketStruct.h
    ${INCROOT}/TcpSocket.h
    ${INCROOT}/Types.h
    ${SRCROOT}/UdpSocket.cpp
    ${SRCROOT}/UdpSocketStruct.h
    ${INCROOT}/UdpSocket.h
)

set(INCROOT ${CMAKE_SOURCE_DIR}/include/SFML/Graphics)
set(SRCROOT ${CMAKE_SOURCE_DIR}/src/SFML/Graphics)

LIST(APPEND SRC 
    ${INCROOT}/Export.h
    ${SRCROOT}/BlendMode.cpp
    ${INCROOT}/BlendMode.h
    ${SRCROOT}/CircleShape.cpp
    ${SRCROOT}/CircleShapeStruct.h
    ${INCROOT}/CircleShape.h
    ${SRCROOT}/Color.cpp
    ${INCROOT}/Color.h
    ${SRCROOT}/ConvertRenderStates.hpp
    ${SRCROOT}/ConvertTransform.hpp
    ${SRCROOT}/ConvexShape.cpp
    ${SRCROOT}/ConvexShapeStruct.h
    ${INCROOT}/ConvexShape.h
    ${SRCROOT}/Font.cpp
    ${SRCROOT}/FontStruct.h
    ${INCROOT}/Font.h
    ${INCROOT}/FontInfo.h
    ${INCROOT}/Glyph.h
    ${SRCROOT}/Image.cpp
    ${SRCROOT}/ImageStruct.h
    ${INCROOT}/Image.h
    ${SRCROOT}/Rect.cpp
    ${INCROOT}/Rect.h
    ${SRCROOT}/RectangleShape.cpp
    ${SRCROOT}/RectangleShapeStruct.h
    ${INCROOT}/RectangleShape.h
    ${SRCROOT}/RenderTexture.cpp
    ${SRCROOT}/RenderTextureStruct.h
    ${INCROOT}/RenderTexture.h
    ${SRCROOT}/RenderWindow.cpp
    ${SRCROOT}/RenderWindowStruct.h
    ${INCROOT}/RenderWindow.h
    ${SRCROOT}/Shader.cpp
    ${SRCROOT}/ShaderStruct.h
    ${INCROOT}/Shader.h
    ${SRCROOT}/Shape.cpp
    ${SRCROOT}/ShapeStruct.h
    ${INCROOT}/Shape.h
    ${SRCROOT}/Sprite.cpp
    ${SRCROOT}/SpriteStruct.h
    ${INCROOT}/Sprite.h
    ${SRCROOT}/Text.cpp
    ${SRCROOT}/TextStruct.h
    ${INCROOT}/Text.h
    ${SRCROOT}/Texture.cpp
    ${SRCROOT}/TextureStruct.h
    ${INCROOT}/Texture.h
    ${SRCROOT}/Transform.cpp
    ${INCROOT}/Transform.h
    ${SRCROOT}/Transformable.cpp
    ${SRCROOT}/TransformableStruct.h
    ${INCROOT}/Transformable.h
    ${INCROOT}/Types.h
    ${INCROOT}/Vertex.h
    ${SRCROOT}/VertexArray.cpp
    ${SRCROOT}/VertexArrayStruct.h
    ${INCROOT}/VertexArray.h
    ${SRCROOT}/View.cpp
    ${SRCROOT}/ViewStruct.h
    ${INCROOT}/View.h
)

set(INCROOT ${CMAKE_SOURCE_DIR}/include/SFML/Audio)
set(SRCROOT ${CMAKE_SOURCE_DIR}/src/SFML/Audio)

LIST(APPEND SRC 
    ${INCROOT}/Export.h
    ${SRCROOT}/Listener.cpp
    ${INCROOT}/Listener.h
    ${SRCROOT}/Music.cpp
    ${SRCROOT}/MusicStruct.h
    ${INCROOT}/Music.h
    ${SRCROOT}/Sound.cpp
    ${SRCROOT}/SoundStruct.h
    ${INCROOT}/Sound.h
    ${SRCROOT}/SoundBuffer.cpp
    ${SRCROOT}/SoundBufferStruct.h
    ${INCROOT}/SoundBuffer.h
    ${SRCROOT}/SoundBufferRecorder.cpp
    ${SRCROOT}/SoundBufferRecorderStruct.h
    ${INCROOT}/SoundBufferRecorder.h
    ${SRCROOT}/SoundRecorder.cpp
    ${SRCROOT}/SoundRecorderStruct.h
    ${INCROOT}/SoundRecorder.h
    ${INCROOT}/SoundStatus.h
    ${SRCROOT}/SoundStream.cpp
    ${SRCROOT}/SoundStreamStruct.h
    ${INCROOT}/SoundStream.h
    ${INCROOT}/Types.h
)

# define the csfml (merged) target
csfml_add_library(csfml
                  SOURCES ${SRC}
                  DEPENDS ${SFML_AUDIO_LIBRARY} ${SFML_GRAPHICS_LIBRARY} ${SFML_NETWORK_LIBRARY} ${SFML_WINDOW_LIBRARY} ${SFML_SYSTEM_LIBRARY} ${SFML_AUDIO_DEPENDENCIES} ${SFML_GRAPHICS_DEPENDENCIES} ${SFML_NETWORK_DEPENDENCIES} ${SFML_WINDOW_DEPENDENCIES} ${SFML_SYSTEM_DEPENDENCIES})
