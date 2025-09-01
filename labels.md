# GitHub Issue Labels - Rise Gaming Player Rankings

This document provides GitHub issue label specifications based on player rankings from the Steam profiles analysis.

## Priority Labels (Based on Player Tier)

### 🏆 Top Tier Labels
```
priority: platinum
Color: #8B5CF6 (Purple)
Description: Top tier VIP donors with 4+ whitelist roles (Score 65+)
Usage: Issues from players like SaS ash, A cool duck, atubofmexicans, Longshaft
```

```
priority: gold
Color: #F59E0B (Amber)
Description: VIP donors with staff positions (Score 50-64)
Usage: Issues from VIP players with admin/dev/mod roles
```

### 💎 VIP Donor Labels
```
donor: vip
Color: #10B981 (Emerald)
Description: VIP donor status - highest financial contributor tier
Usage: All VIP donors (195 users total)
```

```
priority: high-vip
Color: #06B6D4 (Cyan)
Description: VIP donors with multiple whitelist roles
Usage: VIP donors with 2+ faction assignments
```

### 🎖️ Staff & Authority Labels
```
role: staff
Color: #DC2626 (Red)
Description: Server staff members (admin/dev/mod/tsh)
Usage: Players with staff positions regardless of donor status
```

```
role: supervisor
Color: #7C3AED (Violet)
Description: Supervisory positions with elevated permissions
Usage: Players with supervisor=true in whitelist
```

### 🚀 Faction Leadership Labels
```
faction: osf
Color: #059669 (Green-600)
Description: Takistani Security Forces leadership
Usage: OSF whitelisted players
```

```
faction: srt
Color: #0D9488 (Teal-600)
Description: Special Response Team members
Usage: SRT whitelisted players
```

```
faction: vice
Color: #7C2D12 (Orange-800)
Description: Vice faction members
Usage: VICE whitelisted players
```

```
faction: pmc
Color: #374151 (Gray-700)
Description: Private Military Contractor members
Usage: PMC whitelisted players
```

### 💰 Donor Level Labels
```
donor: tier-4
Color: #BE185D (Pink-700)
Description: Level 4 donor - high financial contributor
Usage: Donor level 4 players
```

```
donor: tier-3
Color: #C2410C (Orange-600)
Description: Level 3 donor - significant financial contributor
Usage: Donor level 3 players
```

```
donor: tier-2
Color: #CA8A04 (Yellow-600)
Description: Level 2 donor - moderate financial contributor
Usage: Donor level 2 players
```

```
donor: tier-1
Color: #65A30D (Lime-600)
Description: Level 1 donor - basic financial contributor
Usage: Donor level 1 players
```

### ⚡ Special Status Labels
```
status: combined
Color: #1D4ED8 (Blue-700)
Description: Users who are both donors and whitelisted (147 users)
Usage: Players appearing in both systems
```

```
status: whitelist-only
Color: #6366F1 (Indigo-500)
Description: Whitelisted users without donor status (115 users)
Usage: Non-donor whitelisted players
```

```
status: donor-only
Color: #8B5CF6 (Purple-500)
Description: Donors without whitelist roles (469 users)
Usage: Financial contributors without faction roles
```

## Usage Guidelines

### Issue Priority Assignment
1. **Platinum Priority**: Top 16 users (Score 65+) - Immediate attention
2. **Gold Priority**: VIP staff members (Score 50-64) - High priority
3. **High-VIP**: Other VIP donors - Elevated priority
4. **Staff Role**: Any staff member regardless of donor status
5. **Donor Tiers**: Based on financial contribution level

### Label Combinations
- Use multiple labels for comprehensive player identification
- Example: `priority: platinum` + `donor: vip` + `role: staff` + `faction: osf`
- Combine faction labels for multi-faction players

### Statistics Reference
- **Total Users**: 731 valid profiles
- **Top Tier**: 16 users (Scores 65-83)
- **VIP Donors**: 195 users total
- **Combined Status**: 147 users (donor + whitelist)
- **Staff Members**: Variable count across tiers

## Implementation Notes

1. Labels should be created in GitHub repository settings
2. Use exact color codes provided for consistency
3. Apply labels based on Steam64 ID lookup in profiles
4. Update labels when player status changes
5. Consider automated labeling based on Steam ID recognition

## Color Scheme Logic
- **Purple/Violet**: Top tier and authority roles
- **Gold/Amber**: High-value contributors
- **Green/Emerald**: VIP status and faction roles
- **Blue/Indigo**: Mixed status categories
- **Red**: Staff and critical roles
- **Gradient by tier**: Donor levels use warm-to-cool progression