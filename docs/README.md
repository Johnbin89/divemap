# Divemap Documentation

Welcome to the Divemap documentation. This directory contains comprehensive documentation for the Divemap scuba diving platform.

## 📚 Documentation Index

### 🚀 Getting Started
- **[README.md](./getting-started/README.md)** - Quick start guide and setup instructions

### 🔧 Development
- **[README.md](./development/README.md)** - Development overview, setup, and workflow
- **[Architecture.md](./development/architecture.md)** - System architecture and design
- **[Database.md](./development/database.md)** - Database documentation and migrations
- **[API.md](./development/api.md)** - API documentation and endpoints
- **[Testing.md](./development/testing.md)** - Testing guide (see [TESTING_STRATEGY.md](./TESTING_STRATEGY.md) for comprehensive details)

### 🚀 Deployment
- **[README.md](./deployment/README.md)** - Deployment overview
- **[Fly.io.md](./deployment/fly-io.md)** - Fly.io deployment guide
- **[Docker.md](./deployment/docker.md)** - Docker setup and configuration
- **[Infrastructure.md](./deployment/infrastructure.md)** - Infrastructure details

### 🛡️ Security
- **[README.md](./security/README.md)** - Security overview, measures, and best practices
- **[OAuth Setup.md](./security/oauth-setup.md)** - Google OAuth configuration

### 🔧 Maintenance
- **[README.md](./maintenance/README.md)** - Maintenance overview and troubleshooting
- **[Migrations.md](./maintenance/migrations.md)** - Database migrations guide
- **[Changelog.md](./maintenance/changelog.md)** - Complete change history and API changes

### 📋 Testing Strategy
- **[TESTING_STRATEGY.md](./TESTING_STRATEGY.md)** - Comprehensive testing strategy and procedures

## 📋 Quick Reference

### For New Users
1. Start with **[Getting Started](./getting-started/README.md)** for installation and setup

### For Developers
1. **[Development Overview](./development/README.md)** - Development setup and workflow
2. **[Architecture Documentation](./development/architecture.md)** - System design and components
3. **[API Documentation](./development/api.md)** - API endpoints and usage
4. **[Testing Guide](./development/testing.md)** - Testing procedures (see [TESTING_STRATEGY.md](./TESTING_STRATEGY.md) for details)

### For Deployment
1. **[Deployment Overview](./deployment/README.md)** - Deployment strategies
2. **[Fly.io Guide](./deployment/fly-io.md)** - Cloud deployment instructions
3. **[Docker Setup](./deployment/docker.md)** - Container configuration
4. **[Infrastructure Details](./deployment/infrastructure.md)** - Infrastructure components

### For Security
1. **[Security Overview](./security/README.md)** - Security measures and best practices
2. **[OAuth Setup](./security/oauth-setup.md)** - Authentication configuration

### For Maintenance
1. **[Maintenance Overview](./maintenance/README.md)** - Maintenance procedures and troubleshooting
2. **[Database Migrations](./maintenance/migrations.md)** - Schema change management
3. **[Changelog](./maintenance/changelog.md)** - Complete version history and API changes

## 🔗 Related Files

- `../README.md` - Main project overview
- `../CHANGELOG.md` - Application changelog

## 📝 Documentation Standards

All documentation should:
- Include clear problem statements
- Provide step-by-step solutions
- Include testing procedures
- Document security considerations
- List all affected files
- Include troubleshooting sections
- Use consistent markdown formatting
- Include table of contents for files > 100 lines

## 🚀 Current Status

**Production URLs:**
- **Frontend:** https://divemap.fly.dev
- **Backend API:** https://divemap-backend.fly.dev
- **Database:** Internal network only (`divemap-db.flycast`)

**Recent Updates:**
- ✅ Documentation consolidation completed
- ✅ Removed duplicate content across files
- ✅ Streamlined testing documentation
- ✅ Consolidated security measures
- ✅ Merged troubleshooting into maintenance guide
- ✅ Reduced total documentation files from 22 to 15

## 📊 Documentation Categories

### **Getting Started (1 file)**
- Quick start guide and setup instructions

### **Development (5 files)**
- Architecture, API, database, testing, and development workflow

### **Deployment (4 files)**
- Deployment strategies and infrastructure

### **Security (2 files)**
- Security measures and OAuth setup (consolidated)

### **Maintenance (3 files)**
- Migrations, changelog, and consolidated maintenance/troubleshooting

### **Testing Strategy (1 file)**
- Comprehensive testing strategy and procedures

**Total Documentation Files: 16** (reduced from 22)

## 🔄 Consolidation Summary

### Files Removed
- `docs/security/measures.md` - Content merged into security README
- `docs/maintenance/troubleshooting.md` - Content merged into maintenance README

### Files Streamlined
- `docs/development/testing.md` - Now references comprehensive TESTING_STRATEGY.md
- `docs/getting-started/README.md` - Focused on user setup, technical details moved to development
- `docs/security/README.md` - Consolidated security measures and audit results
- `docs/maintenance/README.md` - Merged troubleshooting procedures

### Benefits Achieved
- **Reduced Redundancy**: Eliminated duplicate content across files
- **Improved Clarity**: Each file now has a clear, focused purpose
- **Better Organization**: Related content grouped logically
- **Easier Maintenance**: Fewer files to update and maintain
- **Clearer Navigation**: Users can find information more quickly 