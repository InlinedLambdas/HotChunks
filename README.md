# HotChunks

:hot_face: *So hot...*

This project is intended to solve a [performant problem](https://github.com/iceBear67/AstralFlow/issues/45#issuecomment-1065874236) from AstralFlow.

# Description

HotChunks will collect chunk-player data to detect some chunks that being loaded very frequently. Then, We'll mark them as `HotChunk`.  

`HotChunk`s will be kept in memory until the *hotspot founder* quit the game. (i.e no one stay in this chunk for a long time).  

This plugin is used to lessen some potential overhead from creating machines and loading machine data. (Especially for [AstralFlow](https://github.com/iceBear67/AstralFlow))

# Status

Low-priority. This is **not*** an important work at now.