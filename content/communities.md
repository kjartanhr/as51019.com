+++
title = "Communities"
date = 2024-05-01T21:51:51Z
author = "Kjartan Hrafnkelsson"
+++

# Community structure

`51019, xnzz` where `x` = location ID; `n` = 0: informational; `n` = 1; action; `z` = community ID.

# Informational BGP communities tagged in all points of presence:

|  Community  | Description                             |
|-------------|-----------------------------------------|
| 51019, x00  | Redistributed to BGP in PoP             |
| 51019, x01  | Learnt from transit in PoP              |
| 51019, x02  | Learnt from customer in PoP             |
| 51019, x03  | Learnt over peering in PoP              |
| 51019, x04  | Learnt from another "backbone" location |

x = location ID.

# Informational BGP communities tagged in Frankfurt 🇩🇪

|  Community  | Description                           |
|-------------|---------------------------------------|
| 51019, 005  | Learnt over LocIX Frankfurt IX fabric |
| 51019, 006  | Learnt over FogIXP IX fabric          |
| 51019, 007  | Learnt over NL-ix IX fabric           |

x = 0

# Informational BGP communities tagged in Amsterdam 🇳🇱

|  Community  | Description                    |
|-------------|--------------------------------|
| 51019, 105  | Learnt over Grunn-IX IX fabric |

x = 1

# Informational BGP communities tagged in Toronto 🇨🇦

|  Community  | Description                |
|-------------|----------------------------|
| 51019, 205  | Learnt over ONIX IX fabric |

x = 2

# Informational BGP communities tagged in London 🇬🇧

|  Community  | Description                 |
|-------------|-----------------------------|
| 51019, 305  | Learnt over LONAP IX fabric |

x = 3

# Informational BGP communities tagged in Fremont 🇺🇸

|  Community  | Description                  |
|-------------|------------------------------|
| 51019, 505  | Learnt over FREMIX IX fabric |

x = 4

# Informational BGP communities tagged in Reykjavík 🇮🇸

|  Community  | Description                 |
|-------------|-----------------------------|
| 51019, 605  | Learnt over REMIX IX fabric |

x = 5