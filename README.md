It's just a TypeScript interface with 1 property:  'data'

To include in your project:

import { IPublicDataContainer } from 'public-data-container-interface/IPublicDataContainer'

Usage:

export ArrayContainerClass implements IPublicDataContainer<any[]> {...}